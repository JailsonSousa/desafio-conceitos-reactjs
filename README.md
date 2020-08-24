<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />

<h3 align="center">
  Desafio 03: Conceitos do ReactJS
</h3>

## 👨🏻‍💻 O que aprendi nesse modulo?

- Conceitos de React.js
- Configurando Babel
- Configurando Webpack
- Componentização
- Estado e Imutabilidade
- Consumindo dados de uma api

## :rocket: Sobre o desafio

Nesse desafio foi colocado em pratica todo conhecimento adquirido no modulo de front end com reactjs.
O desafio consistia em criar uma tela em reactjs para listar, adicionar e remover repositorios utilizando a API [Desafio 02: Conceitos do Node.js](https://github.com/JailsonSousa/desafio-conceitos-nodejs).

**Obs: No desafio poderia utilizar dados estaticos ao adicionar um repositório e o importante era os recursos de adicionar/listar/remover estarem funcionando.**

### Funcionalidades da aplicação

Para concluir o desafio seria necessário criar as seguintes funcionalidade:

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista com o campo **title** de todos os repositórios que estão cadastrados na sua API.

- **`Adicionar um repositório a sua API`**: Deve ser capaz de adicionar um novo item na sua API através de um botão com o texto **Adicionar** e, após a criação, deve ser capaz de exibir o nome dele após o cadastro.

- **`Remover um repositório da sua API`**: Para cada item da sua lista, deve possuir um botão com o texto **Remover** que, ao clicar, irá chamar uma função para remover esse item da lista do seu frontend e da sua API.

### Específicação dos testes

Ao concluir as funcionalidade foi necessário executar o comando **yarn test** no terminal para testar se cada funcionalidade estava de acordo com o que foi pedido.

Em cada teste, tem uma breve descrição do que a aplicação deve cumprir para que o teste passe.

Para esse desafio tivemos os seguintes testes:

- **`should be able to add new repository`**: Para que esse teste passe, sua aplicação deve permitir que um repositório seja adicionado ao seu backend e listado no seu frontend dentro de uma `LI`.

- **`should be able to remove repository`**: Para que esse teste passe, sua aplicação deve permitir que ao clicar no botão de remover que vai estar dentro da `LI` do repositório adicionado, o item seja removido da listagem.

## :calendar: Entrega

A entrega do desafio foi feita na plataforma da Rocketseat, foi necessário enviar o link desse repositório para eles fazerem a avaliação do desafio.
