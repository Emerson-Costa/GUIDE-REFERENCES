# Guia Básico Knex

## Documentação Knex: http://knexjs.org/

### Migrações 

####  Inicia uma conexão

    $npx kenx init

#### Criar uma migração

    $npx knex migrate:make create_table_namers

#### Rodar as migrações

    $npx knex migrate:latest

#### Roda uma migração específica

    $npx knex migrate:up "nome_migracao.js"

#### Listar migração concluídas e pendentes
    $npx knex migrate:list

### Seeds

#### Cria um Seed

    $npx knex seed:make 001_users

#### Roda os Seed

    $npx knex seed:run  

#### Roda um Seed especifico

    $npx knex seed:run --specific "nome_seed.js"  