# DASistemas - TCC1

Este projeto é parte pratica do Trabalho de conclusão de curso, TCC-1.
Nele esta composto um server de dados em Neo4j e para o midleware em Node utilizamos o framework do ApolloServer para implementar a API para o GraphQL server.

## Quickstart

### Docker Compose

Após instalar as dependencias da API é possivel iniciar o docker via:
```
docker-compose up -d
```

Caso seja necessario é possivel povoar o banco de dados via:
```
docker-compose run api npm run seedDb
```

### [`/api`](./api)

*Instalando dependencias API*

```
(cd ./api && npm install)
```

*Iniciando API Server*
```
cd ./api && npm start
```

![](api/img/graphql-playground.png)

