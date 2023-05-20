<img src="https://efficient-sloth-d85.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fef4d7a33-eb32-4e83-8f45-7c3bb87119ff%2Ffavicon.png?id=e3d8fd73-8393-4d03-839b-d85371e63c54&table=block&spaceId=08f749ff-d06d-49a8-a488-9846e081b224&width=200&userId=&cache=v2" alt="Nlw Spacetime">

Para acessar a versão web é só clicar [aqui](https://nlw-spacetime-mocha.vercel.app/)

Este é um projeto feito na Next Level Week ministrado pelo tutor Diego Fernandes

### Objetivo do projeto

Este projeto tem como objetivo aprender uma stack poderosa no mercado hoje.

Foi utilizado as técnologias:

- NodeJs para o backend
- NextJs para o frontend
- React Native para o mobile

### O que é o NLW Spacetime?

É um projeto feito utilizando OAuth para fazer login com GitHub e cadastrar memórias que você queira junto com uma foto e mostrar isso em uma timeline.

## Executar o projeto

#### Backend

##### Variáveis de ambiente
Criar um arquivo `.env` na pasta server e colocar as seguintes variáveis de ambiente:

```
DATABASE_URL="file:./dev.db"
GITHUB_CLIENT_SECRET=
GITHUB_CLIENT_ID=
```

Entre na pasta backend e execute o comando:
`npm install`

Depois de executar o comando acima, é só executar o comando abaixo:
`npm run dev`

O backend já estará executando.

#### Frontend

##### Variáveis de ambiente
Criar um arquivo `.env` na pasta server e colocar as seguintes variáveis de ambiente:

```
NEXT_PUBLIC_GITHUB_CLIENT_ID=
NEXT_PUBLIC_API_URL=http://localhost:3333
```

Entre na pasta frontend e execute o comando:
`npm install`

Depois de executar o comando acima, é só executar o comando abaixo:
`npm run dev`

O frontend já estará executando.

#### Mobile

Entre na pasta frontend e execute o comando:
`npm install`

Depois de executar o comando acima, é só executar o comando abaixo:
`npm start`

O mobile já estará executando.
