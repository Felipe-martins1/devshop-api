# DevShop Api

## Description

<h4 style='color:#5e60ce;'>DevShop API is the backend for DevShop</h4>
</br>

## Developed using

- [<img src="https://nestjs.com/img/logo_text.svg" width="60" align="center" alt="Nest Logo" />](https://github.com/nestjs/nest)

- [<img src="https://github.com/typeorm/typeorm/raw/master/resources/logo_big.png" width="60" align="center" alt="typeorm logo"></img>](https://typeorm.io/#/)

- [<img src="https://camo.githubusercontent.com/1bf20c3280e1ffe2c2d28e8bab1e080fa211733a8844ee7f562ec9494611b3e5/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f312f31372f4772617068514c5f4c6f676f2e7376672f3132303070782d4772617068514c5f4c6f676f2e7376672e706e67" width="30" align="center" alt="Graphql Logo" />](https://graphql.org/)

- [<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/Postgresql_elephant.svg/1200px-Postgresql_elephant.svg.png" width="30" align="center" alt="PostgreSQL Logo" />](https://www.postgresql.org/)

</br>

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Database Migrations

```bash
# generate a new migration synchronizing entities
$ npm run typeorm migration:generate -- -n <migration description>

# sync database running migrations
$ npm run typeorm migration:run
```

## License

[MIT licensed](LICENSE).
