# Comandos Básicos Git

##  Inicia um repositório

    $git init

## Configura o nome e o e-mail do usuário

    $git config --global user.name "Username"
    
    $git config --global user.email "usuário@gmail.com"

## Mostra a situação atual de todos os arquivos 

    $git status   


## Carrega todos os arquivos  para o commit

    $git add .

## Visualizar o histórico de versão

    $git log

## Mostra uma linha de cada commit

    $git log --oneline

## Subir o repositório no GitHub

    $git remote add origin "link_do_repositorio"
    $git push -u origin main