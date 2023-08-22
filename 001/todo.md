# Exercício: Clube de Skate

Imagine que você está administrando um clube de skate e deseja manter um registro dos skatistas e suas manobras. Para isso, você decidirá criar uma classe em JavaScript.

## Instruções

### Classe Skatista

- Crie uma classe chamada Skatista.
- No construtor, a classe deve aceitar dois argumentos: nome e manobras (onde manobras é um array).
- Crie um método chamado adicionarManobra que aceita uma manobra (string) e a adiciona ao array de manobras.
- Crie um método chamado mostrarManobras que imprime todas as manobras do skatista.

### Instanciação

- Instancie dois objetos da classe Skatista, cada um com um nome diferente e pelo menos uma manobra.

### Chamada de funções

- Adicione mais manobras a um dos skatistas usando o método adicionarManobra.
- Mostre as manobras de ambos os skatistas usando o método mostrarManobras.

### Array de Skatistas

- Crie um array chamado clubeSkate.
- Adicione seus skatistas instanciados ao clubeSkate.

### Callbacks

- Escreva uma função chamada apresentacao que aceita um skatista e uma função de callback. Esta função deve imprimir o nome do skatista e, em seguida, chamar a função de callback.
- Use a função apresentacao com um skatista e passe mostrarManobras como callback.

### Código de Início

```javascript
class Skatista {
  // Complete o construtor e os métodos aqui
}

// Instancie seus skatistas aqui

// Adicione manobras e mostre-as aqui

// Crie e manipule o array clubeSkate aqui

// Implemente a função de apresentação e o callback aqui
```

### Dicas

- Lembre-se de que em JavaScript, as classes têm a palavra-chave constructor para inicializar um objeto.
- Para adicionar um item a um array em JavaScript, você pode usar o método push.
- Callbacks são simplesmente funções que são passadas como argumentos para outras funções e são executadas depois.
