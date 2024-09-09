# Fatec Jahu Workshop JS Corrigido

Feito por Bruno Pavan Silva Lallo, aluno de Sistemas para Internet no 4º semestre.

Código NÂO Corrigido: 

```js
const x, y = 5
x + 10

function somar () {
  r = x + y
}

console.log(somar())
```

Código Corrigido abaixo:

```js
let x = 5;
const y = 5;

x += 10;

function somar () {
  return x + y
}

console.log(somar())
```