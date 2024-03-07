### Constantes

Constantes têm o mesmo funcionamento de uma variável, mas como o próprio nome já diz, em uma *constante*, o valor não pode ser modificado após a inicialização. Uma constante pode ser declarada de qualquer uma das maneiras abaixo:

```go
const PI float64 = 3.141592
const PI = 3.141592
```

Caso tente reatribuir um valor para uma constante, o compilador irá retornar um erro na execução do programa:

```go
const PI = 3.141592

PI = 3.14 // Ocorrerá um erro -> "cannot assign to PI"
```