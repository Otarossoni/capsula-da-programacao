### Tipo de Int e Float

Diferente dos tipos `bool` e `string`, os tipos `int` e `float` possui subtipos, onde cada um possui características diferentes.

#### Tipo Int

O tipo `int` tem duas peculiaridades, ele pode variar em tamanho do conteúdo da variável e se permite ou não valores negativos.

Todos os tipos inteiros podem possuir um limitador de tamanho, mensurado conforme a quantidade de bits usados para a variável. Quanto maior o número no tipo, maior o valor suportado:

```go
var numA int8
var numB int16
var numC int32
var numD int64
```

Já todos os tipos `int` que começam com a letra _`u`_(***unsigned***) não permitem valores negativos, já os que não começam com _`u`_(***unsigned***) permitem o uso de valores negativos:

```go
// Não permite valor negativo
var age uint

// Permite valor negativo
var degree int
```

#### Tabela de Abrangência das Variáveis do Tipo Int

|             |                                                                                                               |
| ----------- | ------------------------------------------------------------------------------------------------------------- |
| **int**     | _capacidade: 32bits em sistemas 32bits e 64bits em sistemas 64bits, mas não é um alias para int32 ou int64_   |
| **int8**    | _capacidade: -128 ~ 127_                                                                                      |
| **int16**   | _capacidade: -32.768 ~ 32.767_                                                                                |
| **int32**   | _capacidade: -2.147.483.648 ~ 2.147.483.647_                                                                  |
| **int64**   | _capacidade: -9.223.372.036.854.775.808 ~ 9.223.372.036.854.775.807_                                          |
| **uint**    | _capacidade: 32bits em sistemas 32bits e 64bits em sistemas 64bits, mas não é um alias para uint32 ou uint64_ |
| **uint8**   | _capacidade: 0 ~ 255_                                                                                         |
| **uint16**  | _capacidade: 0 ~ 65.535_                                                                                      |
| **uint32**  | _capacidade: 0 ~ 4.294.967.295_                                                                               |
| **uint64**  | _capacidade: 0 ~ 18.446.744.073.709.551.615_                                                                  |
| **uintptr** | _capacidade: grande o suficiente para guardar o padrão de bits de qualquer ponteiro_                          |
|             |                                                                                                               |

#### Tipo Float

O tipo `float` possui apenas limitadores de capacidade definidos pela [IEEE 754](https://en.wikipedia.org/wiki/IEEE_754), e possui apenas dois tipos, `float32` e `float64`:

```go
var height float32
var weight float64
```

#### Tabela de Abrangência das Variáveis do Tipo Float

|             |                                                              |
| ----------- | ------------------------------------------------------------ |
| **float32** | _capacidade: todos os pontos flutuantes IEEE-754 de 32 bits_ |
| **float64** | _capacidade: todos os pontos flutuantes IEEE-754 de 64 bits_ |
|             |                                                              |