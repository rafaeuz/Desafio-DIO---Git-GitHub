[TOC]

# Comandos git :gear:



## Configuração

`git config --list` : lista as configurações do git

`git config --global user.name "NOME"` : configura nome do usuário

`git config --global user.mail "email@gmail.com"` : configura email do usuário

___

## Inicialização e Uso

`git init` : inicia um repositório local na pasta

`git status` : mostra o status da pasta local (Untracked, Modified, Staged, etc)

`git add *` : adiciona todos (*) os arquivos da pasta ao Stage

`git commit -m "comentário"` : Cria o commit com os arquivos no Stage para ser enviado ao GitHub

`git push origin main` : envia projeto para o repositório remoto GitHub no branch main

`git pull origin main`: atualiza o projeto local com o projeto remoto do GitHub no branch main

`git clone` : clona o projeto designado pela https ou ssh para o computador

___

## Adicionar repositório criado no GitHub

`git remote add origin git@github.com:xxxx/xxx.git` :  Adiciona o repositório remoto com o alias origin

`git remote -v` : Mostra os repositórios remotos

### Criar branch

`git branch XXXXX`  : Cria branch com nome xxxxx

`git checkout xxx` : Muda a árvore de trabalho
