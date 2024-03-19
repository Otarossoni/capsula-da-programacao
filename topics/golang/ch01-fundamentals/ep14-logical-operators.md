### Operadores Lógicos

Os operadores lógicos se aplicam entre resultados de operadores relacionais, pois permitem fazer operações lógicas entre os resultados de relacionamentos relacionais. Como no exemplo abaixo:

```go
age := 18
isWoman := true

isValidPerson := age >= 18 && isWoman == true
```

Observe que o operador `&&` verifica se tanto a operação da esquerda quanto a da direita são verdadeiras, se sim, o resultado da variável `isValidPerson` também será verdadeiro.
Abaixo todos os operadores lógicos:

| Nome  | Operador |
| :---- | :------- |
| E     | `&&`     |
| Ou    | \| \|    |
| Igual | `==`     |