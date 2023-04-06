# OpenTelemetry example
Esse é um projeto de exemplo para o OpenTelemetry, onde rodamos o Next e ele exporta dados para o Jaeger.

## Requisitos
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Docker Compose](https://img.shields.io/badge/docker%20compose-%231572B6.svg?style=for-the-badge&logo=docker&logoColor=white)](https://docs.docker.com/compose/)
[![Node](https://img.shields.io/badge/node-%2343853D.svg?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/en/)
[![Npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/)

## Como rodar
1. Primeiro, precisamos instalar as dependências do projeto:
```bash
npm install
```

2. Depois, precisamos subir o docker-compose:
```bash
docker compose up
```
ou
```bash
docker-compose up
```

3. Por fim, podemos rodar o projeto:
```bash
npm run dev
```

## Como testar
1. Acesse o [localhost:16686](http://localhost:16686) para ver os dados no Jaeger.

## Resultado
![Print](./.github/print.png)

## Referências
- [OpenTelemetry](https://opentelemetry.io/)
