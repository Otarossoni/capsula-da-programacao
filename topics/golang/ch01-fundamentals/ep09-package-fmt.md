### Pacote Fmt

O `fmt` é um pacote interno do Golang, e pode ser importado nativamente em qualquer arquivo `.go`. O comportamento comum desse pacote é o de _printar_ algo no _console_ da aplicação, ou seja, mostra o resultado de qualquer variável, entretanto, ele possui algumas outras funcionalidades, abaixo segue um exemplo de uso do pacote `fmt`.

```go
package main

import "fmt"

func main() {
  var sum = 5 + 5
  fmt.Println(sum) // Mostra no console o resultado 10
}
```

Entretanto, o pacote pode ter outros comportamentos, como formatar o conteúdo de uma variável antes de exibir, ou até mesmo manipular valores internos. Abaixo segue uma lista de alguns outros métodos disponíveis no pacote:

| Método | Função |
| :--- | :--- |
| fmt.Print | Printa no console |
| fmt.Println | Printa no console, com quebra de linha |
| fmt.Printf | Printa no console com formatações |
| fmt.Scan | Obtém o valor digitado no console |