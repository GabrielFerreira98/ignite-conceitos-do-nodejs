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

## 🧑‍💻 Tecnologias utilizadas

- [NodeJS](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [Insomnia](https://insomnia.rest/)

## 📌 Index

- [Instalando as ferramentas]()
  - [Instalando o NodeJS]
  - [Instalando o Yarn]
  - [Instalando o Insomnia]
- [Executando o Projeto]
- [Inicializando o Projeto]()
- [Requisitos da aplicação](https://github.com/GabrielFerreira98/ignite-conceitos-do-nodejs/blob/main/README.md#requisitos-da-aplica%C3%A7%C3%A3o)
  - Requisitos de Usuário
  - Requisitos de To-do

## 🧰 Instalando as Ferramentas 

Os passos desse tópico foram realizados no sistema operacional do Windows.

### Instalando o NodeJS

É possível fazer o download pelo [Site oficial do NodeJS](https://nodejs.org/en/download/)

Após o download, abra o Windos PowerShell no modo administrador e digite a seguinte linha de código para ver se o Node foi instalado corretamente:

```
node -v
```

### Instalando o Yarn

O Yarn é o gerenciador de pacotes que será utilizado para baixar todas as dependências e executar o projeto. Caso você deseje fazer com o NPM, pode pular esta etapa.
Há duas possibilidades de baixar o Yarn

1. Pelo site oficial do [Yarn](https://yarnpkg.com/)
2. Rodar o seguinte comando no terminal:
```
npm install -g yarn
```

### Instalando o Insomnia

Pode ser baixado pelo próprio site do [Insomnia](https://insomnia.rest/download)

## 🚀 Executando o projeto

Faça o clone do projeto no Powershell 

```
#faça o clone do projeto
git clone 

#entre na pasta baixada
cd ignite-conceitos-do-nodejs
```

### Abrindo o projeto

Abra o projeto utilizando alguma IDE. Esse projeto foi feito utilizando o [VSCode](https://code.visualstudio.com/)

### Instalando as dependências

Instale as dependências do projeto utilizando a seguinte linha de comando:

```
yarn install
```

## 🏃 Inicializando o projeto

Rode a linha de comando

```
yarn run dev
```

Mantenha o terminal rodando para utilizar o projeto

## 🖥️ API

### Requisitos da Aplicação

#### Requisitos de usuário

1. Deve ser possível criar um usuário
2. Não deve ser possível criar um usuário com um username existente

#### Requisitos de To-do's

1. Deve ser possível listar todos os to-do's de um usuário
2. Deve ser possível criar um novo to-do
3. Deve ser possível atualizar um to-do
4. Não deve ser possível atualizar um to-do não existente
5. Deve ser possível marcar um to-do como feito
6. Não deve ser possível marcar um to-do não existente como feito
7. Deve ser possível deletar um to-do
8. Não deve ser possível deletar um to-do não existente

- post/users
- get/todos
- post/todos
- put/todos/:id
- patch/todos/:id/done
- delete/todos/:id



