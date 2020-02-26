# GoBarber
Projeto criando durante o curso de bootcamp do RocketSeat

## Dependencias
* jsonwebtoken
* node 13
* yarn 1.22
* eslint

## Using eslint
` yarn eslint --fix src --ext .js`

## Docker

`docker run --name database -e POSTGRES_PASSWORD=docker -p5432:5432 -d postgres`

`docker run --name mongobarber -p 27017:27017 -d -t mongo`


## Squelize

`$ yarn sequelize migration:create --name=create-user` Create table user

`$ yarn sequelize db:migrate` add proprides of table