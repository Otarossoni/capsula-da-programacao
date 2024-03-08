### Declaração Múltipla de Variáveis

Para encurtar a declaração de muitas variáveis em sequência, é possível utilizar a *Declaração Múltipla de Variáveis*, que através de apenas um uso da palavra `var`, é possível declarar e/ou inicializar infinitas variáveis ao mesmo tempo, e isso pode ser feito de duas formas, com várias variáveis de mesmo tipo e com variáveis de tipo diferentes, como exemplificado abaixo:

```go
// Sem Declaração Múltipla de Variáveis
var a bool    = true
var b int     = 10
var c string  = "Otávio"
var d float64 = 1.2

// Com Declaração Múltipla de Variáveis de Tipos Diferentes
var (
  a bool    = true
	b int     = 10
	c string  = "Otávio"
	d float64 = 1.2
)

// Com Declaração Múltipla de Variáveis de Tipos Iguais
var a, b, c, d int = 2, 5, 6, 9
```