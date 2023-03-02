# CONFIGURAÇÃO INICIAL
> Comandos básicos para configurar o Git.
> O Git já deve estar instalado em seu Windows ou Linux.

## Listar todas as configurações
$ git config --list

## Alterar o User.Name
$ git config --global user.name "Pedro Paulo Bento de Souza"

## Alterar o User.email
$ git config --global user.email "seu.email@gmail.com"

## Configurando o editor de código padrão
$ git config --global core.editor vscode

## Definir o Branch padrão como MAIN
$ git config --global init.defaultBranch main

## --global -> escopo da configuração do usuário. Especificação somente para o usuário.
## Visualizar o arquivo gitconfig
$ cat ~/.gitconfig

## Escopo sistêmico que abrange todos os usuários do PC que tem o Git instalado
$ git config --system core.editor vscode
$ git config --system init.defaultBranch main

## Hierarquia de configuração
1. Escopo Global de usuário sobreescreve System;
2. Escopo de Projeto sobreescreve Global;




