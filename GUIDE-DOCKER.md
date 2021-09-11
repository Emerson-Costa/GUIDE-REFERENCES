# Comandos Básicos do Docker 

## 1- Iniciando o docker

    $sudo service docker start

## 2- Puxando uma imagem do servidor

 	$docker pull "nome_imagem"

 ### Exemplo:

    $docker pull postgres:alpine

## 3- Criando um container

	$docker run --name "nome_container" + Atributos_adicionais

### Exemplo:

    $docker run --name postgres-0 -e POSTGRES_PASSWORD=123456 -d -p 5432:5432 postgres:alpine

## 4- Executando uma imagem

    $docker exec -it "nome_container" bash

###  Exemplo:

    $docker exec -it postgres-0 bash

##### Documentação:  https://docs.docker.com/get-started/overview/