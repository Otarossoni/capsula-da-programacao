### Tipos de Dados Primitivos

Toda variável precisa possuir um tipo, que diz aquilo que pode ser guardado dentro dela (algo que garante que na caixa de `brinquedos` só entrarão brinquedos de fato). Em Golang, existem quatro tipos de dados primitivos, são eles: `int`, `float`, `string` e `bool`.

#### Tipagem por Declaração

Na tipagem por declaração, é necessário expor claramente o tipo da variável, e só pode ser realizada sem o [Operador Curto de Declaração](/topics/golang/ch01-fundamentals//ep03-short-variable-declaration-operator.md), como abaixo:

```go
var message string
var age int32
var height float64
var isKid bool
```

#### Tipagem por Inferência

Já na tipagem por inferência, não é necessária a exposição do tipo, pois o próprio compilador já faz isso automaticamente, baseado no valor atribuído para a variável. Nesse caso, é possível utilizar ambos os métodos, com e sem o [Operador Curto de Declaração](/topics/golang/ch01-fundamentals//ep03-short-variable-declaration-operator.md), como nos exemplos abaixo:

```go
var message = "Hello world!"
var age = 21
var height = 72.9
var isKid = false

// or

message := "Hello world!"
age := 21
height := 72.9
isKid := false
```

#### Tipo Int

O tipo `int`, é usado para guardar números inteiros, que não precisem do valor das casas decimais, como no exemplo abaixo:

```go
var age int = 21
```

#### Tipo Float

Já o tipo `float` é usado para quando o valor das casas decimais são relevantes em algum grau, como no exemplo abaixo:

```go
var height float64 = 72.9
```

#### Tipo String

O tipo `string` geralmente é muito comparado a texto puro, por mais que, por debaixo dos panos, não seja exatamente isso, entretanto é um bom exemplo para exemplificar o conceito, que está abaixo:

```go
var message string = "Hello world!"
```

#### Tipo Bool

O tipo `bool` é como um interruptor, que pode estar ligado ou desligado, acesso ou apagado, sim ou não, verdadeiro ou falso. Em uma variável do tipo `bool`, pode haver apenas um de dois valores, `true` ou `false`, como mostrado abaixo:

```go
var isKid bool = false
var itsOld bool = true
```