# Criar uma TAG de versão final
> Utilizado para criar um marco como o fechamento de uma versão 1.0, 2.0, 3.0...

## Listar as tags do repositório
$ git tag

## Acesse a branch main
$ git checkout main

## Criar uma tag
$ git tag -a v2.0 -m "Versão 2.0"

## Visualise a tag criada
$ git tag

## Mesmo que tenha esquecido de criar a Versão 1.0 da tag. Isso pode ser feito dessa forma:
1. [Copie o hash do commit que será criado a tag Versão 1.0]:
$ git log
2. [Crie a tag da versão 1.0]:
$ git tag -a v1.0 -m "Versão 1.0" 30e35e7cdab46aed20e54573ed69f508286abf5b

## Visualise as tags:
$ git tag
v1.0
v2.0

## Visualizar os detalhes da tag:
$ git show v2.0

## (CUIDADO!) Remover uma tag:
$ git tag -d v2.0

