# Youtube clone with Express, MongoDB, & TypeScript

This repository is not intended for commercial use.

It was created just as a code sample and doesn't have a lot of features.

## Features

1. Register user
2. Login
3. Get current logged in user
4. Upload video
5. Get all videos
6. Stream a video

## Technologies

* [Docker](https://docker.com)

### Backend

* [Express](https://expressjs.com/)
* [Mongoose](https://www.mongodb.com/)
* [TypeScript](https://www.typescriptlang.org/)
* [argon2](https://www.npmjs.com/package/argon2)
* [busboy](https://www.npmjs.com/package/busboy)
* [pino](https://github.com/pinojs/pino)
* [Zod](https://github.com/colinhacks/zod)

### Frontend

* [Next.js](https://nextjs.org/)
* [Mantine](https://mantine.dev/)
* [TypeScript](https://www.typescriptlang.org/)
* [React Query](https://react-query.tanstack.com/)

## Installation

### Server

install server dependencies

```sh
cd server

cp .env.example .env

npm i

```

### Client

install server dependencies

```sh
cd client

cp .env.example .env

npm i

```

## Running/shutting down the app

### Local option (docker installed locally)

run **npm i** on both server and client folders

```sh
npm i
```

To stop use **ctrl + c** keyboard command

### Docker option (run client locally and server on container)

To start Docker server run **docker up -d** command. On the first time docker will install the containers.

1. Start client locally with **npm i**

```sh
cd client

npm run prod
```

2. Run server on Docker container

```sh
cd server

docker-compose up -d
```

To stop docker use **ctrl + c** keyboard command

## License

This project is licensed under the MIT license. For more information see the [LICENSE](LICENSE.md) file.
