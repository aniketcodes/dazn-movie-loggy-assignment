## Setup
Create a .env file and populate the contents from .env.sample

## Docker
```bash
$ docker build -t dazn-movie-lobby-assignment .
$ docker run -p 3000:3000 dazn-movie-lobby-assignment
```

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

To view the test cases, please checkout to feature/testCases

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```


## License

Nest is [MIT licensed](LICENSE).
