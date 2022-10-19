 # 🖥️ Conceitos do Node.js - Ignite - Rocketseat

Essa é uma aplicação para gerenciar tarefas (*to-do's*). 
É permitida a criação de um usuário com name e username, bem como fazer o CRUD de todos:

- Criar um novo *to-do*;
- Listar todos os *to-dos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *to-do* como feito;
- Excluir um *to-do*;

Tudo isso para cada usuário em específico (o username será passado pelo header).

Esse é o desafio 01 do primeiro módulo da trilha de NodeJS do Ignite da Rocketseat. O desafio está disponível no seguinte link:

https://www.notion.so/Desafio-01-Conceitos-do-Node-js-59ccb235aecd43a6a06bf09a24e7ede8#31772e343719426181b6c799ecb4ef55

# 🧑‍💻 Tecnologias utilizadas

O projeto foi realizado utilizando os conceitos iniciais do Node.js e a biblioteca Express

- [NodeJS](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)

# 📌 Index

- Instalando as ferramentas
  - Baixando o Yarn


## Rotas da Aplicação

- post/users
- get/todos
- post/todos
- put/todos/:id
- patch/todos/:id/done
- delete/todos/:id

## Requisitos da Aplicação

### Requisitos de usuário

1. Deve ser possível criar um usuário
2. Não deve ser possível criar um usuário com um username existente

### Requisitos de To-do's

1. Deve ser possível listar todos os to-do's de um usuário
2. Deve ser possível criar um novo to-do
3. Deve ser possível atualizar um to-do
4. Não deve ser possível atualizar um to-do não existente
5. Deve ser possível marcar um to-do como feito
6. Não deve ser possível marcar um to-do não existente como feito
7. Deve ser possível deletar um to-do
8. Não deve ser possível deletar um to-do não existente

## Para testar o projeto

Primeiro é necessário clonar o repositório.

Após a clonagem, digite o comando:

  "yarn install"
  
Após isso, há duas maneiras de se testar:

1. Utilizando o Postman ou Insomnia no localhost:3333
2. Utilizando o comando "yarn test" no próprio projeto.
