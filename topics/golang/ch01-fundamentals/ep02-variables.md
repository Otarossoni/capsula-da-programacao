# Variáveis

Apossando-se do exemplo mais comum sobre o assunto, variáveis são como caixas (ou gavetas) nomeadas, que podem guardar dados dentro de si. Por exemplo, uma variável pode se chamar `brinquedos`, e pode guardar valores como `carrinho`, `boneca` ou `cubo mágico`. Pode também guardar valores numéricos, como, por exemplo, é possível criar uma variável chamada `lapiseirasPretas` e outra `lapiseirasAzuis`, e seus valores podem ser números inteiros, 4 e 3, respectivamente.

### Declaração

Em Golang, o ato de *declarar* uma variável é criá-la, é atribuir um nome e um tipo para um determinado endereço de memória, dessa forma:

```go
// Declaração
var lapiseirasPretas
```

No código acima, o _compilador_ do Golang irá atribuir o nome `lapiseirasPretas` para alguma pequena parte da memória RAM disponível do computador, essa seria a criação da caixa.

### Inicialização

Quando uma variável é declarada, mas não recebe nenhum dado, ela não foi inicializada, entretanto, o ato de atribuir o primeiro valor para uma variável é chamado de *inicialização*. Como mostrado no exemplo abaixo:

```go
// Declaração
var lapiseirasPretas
// Inicialização
lapiseirasPretas = 4
```

A partir do momento que uma variável tem algum dado dentro dela, ela pode ser considerada como inicializada.

### Atribuição

Depois de uma variável já possuir um valor inicializado, esse valor pode mudar conforme a necessidade, recebendo um novo valor, como abaixo:

```go
// Declaração
var lapiseirasPretas
// Inicialização
lapiseirasPretas = 4
// Atribuição
lapiseirasPretas = 5
```

A partir disso, todo novo valor que essa variável receber será uma *atribuição*.