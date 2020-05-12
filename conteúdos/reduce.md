# Reduce

## Descrição
Método JS que itera sobre um array e utiliza o valor de cada item para criar um objeto final com base em alguma regra.

## Como faz?

```js
array.reduce((acumulador, itensDoArray) => {
    return acumulador + itensDoArray
}, valorInicial)

```

## Dá um exemplo aê!

```js
const numeros = [2, 2, 2, 2, 2, 2]

const total = numeros.reduce((total, numero) => {
  return total + numero
}, 0)

console.log(total)

// 12

```
