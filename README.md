<h1 align="center">Sp Comments</h1>

  <p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/pedroleinar/api-comment-simple-version">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/pedroleinar/api-comment-simple-version">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/pedroleinar/api-comment-simple-version">

  <a href="https://github.com/pedroleinar/api-comment-simple-version/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/pedroleinar/api-comment-simple-version">
  </a>

  </p>

## Projeto

API para gerenciar usuários, comentarios, e votos para avaliação de comentarios.

## Tecnologias

Esta aplicação foi desenvolvida com as tecnologias abaixo:

-   [Typescript](https://www.typescriptlang.org/)
-   [Node.js](https://nodejs.org/en/)
-   [Express](https://expressjs.com/pt-br/)
-   [Typeorm](https://typeorm.io/#/)
-   [JWT-token](https://jwt.io/)
-   [Bcryptjs](https://www.npmjs.com/package/bcryptjs)
-   [uuid v4](https://github.com/thenativeweb/uuidv4/)
-   [Docker](https://www.docker.com/products/docker-desktop)
-   [PostgreSQL](https://www.postgresql.org/)
-   [Eslint](https://eslint.org/)
-   [Prettier](https://prettier.io/)
-   [EditorConfig](https://editorconfig.org/)

---

## how to use

### Requirements

-   [Node.js](https://nodejs.org/en/)
-   [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/)
-   [Docker](https://www.docker.com/products/docker-desktop)

```bash
# Clone this repository
$ git clone https://github.com/pedroleinar/nodejs-server-api-typescript-SpComments.git

# Go into the repository
$ cd nodejs-server-api-typescript-SpComments

# Install dependencies
$ yarn install

# Create the instance of postgreSQL using docker
$ sudo docker run --name spcomments_postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres

# Create a image SpComments in docker
# Connect with docker database containers
# Once the services are running, run the migrations

$ yarn typeorm migration:run
# To finish, run the api service

$ yarn dev:server
# Well done, project is started!
```

---

Feito com 💜 Pedro Gomes 👋 [Meu Linkedin](https://www.linkedin.com/in/pedroleinar/)
