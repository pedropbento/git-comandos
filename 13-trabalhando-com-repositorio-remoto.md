# Trababalhado com repositório remoto
> Como trabalhar localmente e subir as alterações para o repositorio remoto (gitHub)

## Crie uma branch localmente para as alterações
$ git checkout -b novaBranch

## Apos alterações faça o ADD e COMMIT:
$ git add .
$ git commit -m "Alterações locais."

## Enviar alterações para GitHub, porém vinculando a uma Branch em Origin Main
$ git push --set-upstream origin novaBranch

## Fazer o Merge da novaBranch com o Main local.
$ git merge novaBranch

## Subir as alterações do Main local para Origen Main:
$ git push

## E para Baixar as alterações do repostitório remoto usamos o comando Pull:
$ git pull

## Dicas:
> 1. Comando para visualizar as branchs local:
> $ git branch
> 2. Comando para visualizar as branchs remota:
> $ git branch -r







