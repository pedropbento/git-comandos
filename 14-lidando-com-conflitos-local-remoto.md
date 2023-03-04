# Lidando com conflitos
> Alguns exemplos de conflitos que podem surgir com o trabalho em equipe.

## Sempre executar a atualização de seu repositório local:
$ git pull

> [CASE-1] Se você tiver alterado algum arquivo antes do pull e no repositório remoto já tiver diferente de seu local, um erro será retornado ao execugar "git pull".

## A solução para o CASE-1 é configurar a decisão que o git tomará nessa situação:
$ git config pull.rebase false

> [CASE-2] Foi alterado um arquivo local e também teve alteração no mesmo arquivo remoto. Ao executar localmente o "git pull" será retornado "CONFLICT (content): Merge conflict..."

## A solução do CASE-2 é:
1. Editar o arquivo local e localizar os trexos marcados e resolver o conflito unindo os código ou assumindo o local:

<  <<<<<<<< HEAD
<  aqui o código do arquivo local
<  ========
<  aqui o código do arquivo remoto
<  >>>>>>>> 36abb01668f469b7900b096dc2455721db219e0c

2. Resolvido o conflito é seguir com os comandos:
$ git add .
$ git commit -m "Resolvndo conflito."
$ git push





