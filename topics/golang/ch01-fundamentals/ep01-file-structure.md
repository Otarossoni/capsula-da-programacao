# Estrutura de um arquivo .go

Um arquivo `.go` é construído por três segmentos principais. São elas:

- `package`: onde é declarado o nome do pacote que é o arquivo em si, que não possui regra para nome, o que importa de verdade é o nome do package, que em uma aplicação Golang, precisa obrigatoriamente possuir uma `package` de nome `main`;

- `import`: logo abaixo do nome do pacote, é a área onde são importados todos os módulos externos;

- `body`: no corpo do arquivo é onde o código é propriamente implementado, é onde também precisa existir uma função chamada `main`, pois todo programa Golang precisa começar e terminar em um `package main` e em uma função `main`.

###### Exemplo

Para exemplificar as três partes em um arquivo funcional, abaixo segue código:

```go
// Segmento "package"
package main

// Segmento "import"
import "fmt"

// Segmento "body"
func main() {
	fmt.Println("Hello, 世界")
}
```

