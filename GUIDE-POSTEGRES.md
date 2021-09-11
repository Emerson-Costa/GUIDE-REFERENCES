# Guia Básico Postegres

## Documentação postgres: http://pgdocptbr.sourceforge.net/pg82/app-psql.html

### Ajuda

    $psql --help

### Listar os comandos SQL

    $\h
-> \h "comando" : mostra os detalhes do comando

### Entrar no psql

    $psql -U postgres

### Sair do psql

    $\q

### Mostrando todos os bancos

    $\list

### Entrando no banco

    $\c "nome_banco"

### Mostrando as Tabelas do banco

    $\dt

### Entrando em uma tabela

    $\d "nome_tabela"