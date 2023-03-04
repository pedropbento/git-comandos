# Git Log
> Ferramenta para rastrear as mudanças nos repositórios locais e remoto.

## Visualizar todos os logs - mostrará todos os commits no repositório local e remoto em sua linha do tempo.
$ git log

## Visualizar um arquivo.
$ git log arquivo.txt

## Visualizar os logs em uma linha:
$ git log --oneline

## Visualizar os logs com inserções e deleções:
$ git log --stat

## Pode fazer a junção desses comandos:
$ git log --oneline --stat

## Mostrar todas as alterações feitas nos arquivos:
$ git log -p

## Mostrar certa quantidades de logs feitos.
$ git log -n 1
$ git log -n 2
$ git log -n 5

## Mostrar os logs e as branchs criadas e/ou juntadas:
$ git log --graph
$ git log --graph --oneline

## Mostrar os logs de um determinado autor:
$ git log --author="Pedro"












