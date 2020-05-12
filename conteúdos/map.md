# Map

## Descrição
Método JS disponível em arrays (listas) que recebe um item da lista e deve retornar um novo item, o mesmo item alterado, ou partes do item.

Utilização para transformação de dados em listas. O `map` sempre vai retornar uma **nova** lista.

## Como faz?

```js
// gerando uma lista só com os ids dos items
array.map(item => item.id)
```

## Dá um exemplo aê!

```js
const pessoas = [
  { nome: 'miguel', idade: 18 },
  { nome: 'marcos', idade: 19 },
  { nome: 'kaio', idade: 20 }
]

const nomes = pessoas.map(pessoa => pessoa.nome)

console.log(nomes)

// ['miguel', 'marcos', 'kaio]
```
