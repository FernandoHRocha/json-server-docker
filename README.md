# API para testes

Servidor web utilizando API Rest.
## Rodando a aplicação
É necessário ter o [Docker](https://www.docker.com) instalado.
Na pasta raiz do projeto, rodar o comando:
```
docker-compose up -d
```

## Utilizando a API
Para garantir que o container Docker está ativo, execute o comando:
```
docker container ls
```
A aplicação rodará em localhost:3001 e aceita os métodos GET, POST, PUT e DELETE nas suas requisições.
Utilizando a rota da seguinte forma:

localhost:3001/{o modelo ao qual vocês estará se referindo}

A persistência dos dados ocorre no arquivo /backend/test.json, já contendo os modelos:
  - veículos (vehicle)
  - abastecimentos (fuel)

# API for tests

API web server.

## Running the application
Need [Docker](https://www.docker.com).
In the main folder run command:
```
docker-compose up -d
```

## Using the API
To get the application state run command:
```
docker container ls
```
We need to send a http request (GET, POST, PUT, DELETE) to: localhost:3001/{add here what model you want to get}

The file test.json is the database.
