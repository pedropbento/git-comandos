# GERENCIANDO BRANCHS
> Criar ramificações ("multiversos") do branch principal (main) para que as alterações só retornem ao main quando concluidas.

##  Criando uma BRANCH:
$ git branch feature/geren_branch

## Visualizar as BRANCHS:
$ git branch

## Selecionar a BRANCH que irá trabalhar:
$ git checkout feature/geren_branch

## (DICA) Comando para criar e já mudar para BRANCH recem criada:
$ git checkout -b feature/novo_arquivo

## Mudar o nome do BRANCH:
$ git branch -m feature/novo_arquivo

## DELETAR uma BRANCH com -d (minusculo) caso não tenha feito COMMIT:
$ git branch -d feature/novo_arquivo

## DELETAR uma BRANCH com -D (maiusculo) caso tenha feito COMMIT:
$ git branch -D feature/novo_arquivo

