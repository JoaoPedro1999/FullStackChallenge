# FullStackChallenge

## IncFinances

Blog with Space News

## Requisites for running the Back End

Before you begin, you will need to have the following tools installed on your machine:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).

## Running the Back End (server)

### Deployed at: [Deploy](https://fullstackchallengeserver.herokuapp.com/)

### Clone this repository

$ git clone https://github.com/JoaoPedro1999/FullStackChallengeServer.git

### Go to the server folder

$ cd FullStackChallengeServer

### Install the dependencies

$ yarn

### Run the application in development mode

Before run, change the path on this archive **src/shared/infra/database/typeOrmClient.ts**. Change **dist** to src on line 10 and 11.

### Run the application in development mode

$ yarn dev:server

### The server will start at port: 3332 - go to <http://localhost:3332/>

## Running the FrontEnd

### Deployed at: [Deploy](https://fullstackchallengefrontend.joaopedrobeckland.dev/)

### Clone this repository

$ git clone https://github.com/JoaoPedro1999/FullStackChallengeFrontend.git

### Go to the frontend folder

$ cd FullStackChallengeFrontend

### Install the dependencies

$ yarn

#### To run in local mode, change the archive src/services/api.ts

baseURL: 'http://localhost:3332'

### Run the application in development mode

$ yarn dev

### Run the application in development mode

Adding **?admin=true** on URL, you can see the options to create, edit and delete an article

## Tecnologias

The following tools were used in the development of the IncFinances application:

#### Backend

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)

#### Frontend

- [React](https://pt-br.reactjs.org/)
- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)

## Apresentatition

- [Video](https://drive.google.com/file/d/158InjAaycNq2TwEdH8GykCnlbOd7y4s3/view?usp=sharing)

## Developer

 <img style="border-radius: 50%;" src="https://avatars3.githubusercontent.com/u/28880525?s=400&u=d81c22a8b60e75b36a01a52597036a650bfdd9aa&v=4" width="100px;" alt=""/>
 <br />
 <sub><b>João Pedro Beck Land</b></sub>

[![Gmail Badge](https://img.shields.io/badge/-joaopedrobeckland@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:joaopedrobeckland@gmail.com)](mailto:joaopedrobecklandgmail.com)

> This is a challenge by [Coodesh](https://coodesh.com/)
