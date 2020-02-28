<h1 align="center">
    <img alt="GoBarber API" src="https://res.cloudinary.com/lukemorales/image/upload/v1564533051/readme_logos/gobarber_hg5ddx.png" />
    <br>
    GoBarber API
</h1>

<h4 align="center">
  Um aplicativo de agendamento de barbeiro que permite aos usuários agendar uma consulta com seu barbeiro favorito e mostra ao barbeiro sua agenda para o dia.
</h4>

## :rocket: Tecnologias

Esse projeto foi desenvolvido no [RocketSeat GoStack Bootcamp](https://rocketseat.com.br/bootcamp) com as seguintes tecnologias:

-  [Node.js][nodejs]
-  [Express](https://expressjs.com/)
-  [nodemon](https://nodemon.io/)
-  [Sucrase](https://github.com/alangpierce/sucrase)
-  [Docker](https://www.docker.com/docker-community)
-  [Sequelize](http://docs.sequelizejs.com/)
-  [PostgreSQL](https://www.postgresql.org/)
-  [node-postgres](https://www.npmjs.com/package/pg)
-  [Redis](https://redis.io/)
-  [MongoDB](https://www.mongodb.com/)
-  [Mongoose](https://mongoosejs.com/)
-  [JWT](https://jwt.io/)
-  [Multer](https://github.com/expressjs/multer)
-  [Bcrypt](https://www.npmjs.com/package/bcrypt)
-  [Youch](https://www.npmjs.com/package/youch)
-  [Yup](https://www.npmjs.com/package/yup)
-  [Bee Queue](https://www.npmjs.com/package/bcrypt)
-  [Nodemailer](https://nodemailer.com/about/)
-  [date-fns](https://date-fns.org/)
-  [Sentry](https://sentry.io/)
-  [DotEnv](https://www.npmjs.com/package/dotenv)
-  [VS Code][vc] with [ESLint][vceslint]

## Instalação

Clone o projeto com

```sh
git clone https://github.com/ARTHURPC03/GoBarber
```

Entre na pasta do projeto e instale as dependências com:

```sh
yarn
```

Em seguida, você deve criar seu banco de dados do postgres (ou outro se desejar) e preencher seus próprios campos no arquivo .env.

Agora, você precisa criar tabelas com o comando:

```sh
npx sequelize db:migrate
```

Após a configuração do banco de dados, você pode iniciar o servidor com:

```sh
yarn start
```

Se você estiver no ambiente de desenvolvimento, poderá usar o servidor de desenvolvimento:

```sh
yarn dev
yarn queue
```



Feito por ARTHUR PC :wave: [Entre em contato!](https://www.linkedin.com/in/arthurpc03/)

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
