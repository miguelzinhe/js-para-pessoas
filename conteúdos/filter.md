# Filter

## Descrição
Método JS que recebe uma condição que deve retornar `true` ou `false`.

Retorno `true`: item entra em um novo array

Retorno `false`: item não entra em um novo array

## Como faz?

```js
array.filter(item => item != algumaCoisaQueTenhaNoArrayOriginal)

```

## Dá um exemplo aê!

```js
const cores = ['rosa', 'roxo', 'azul', 'vermelho', 'amarelo']

const coresDaora = cores.filter(cor => cor != 'vermelho')

console.log(coresDaora)

// ['rosa', 'roxo', 'azul', 'amarelo']

```
