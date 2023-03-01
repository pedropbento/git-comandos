# MERGE
> Juntar as alterações feitas no BRANCH no MAIN (branch principal).

# 1 - Confirme que esta no BRANCH da ramificação:
$ git branch

# 1.1 - Se não tiver no BRANCH correto, mude para ele:
$ git checkout feature/novo_arquivo

# 2 - Adicione a State Area as alterações desse BRANCH:
$ git add .

# 3 - Faça o commit:
$ git commit -m "Adicionando alterações do BRANCH."

# 4 - Fazer o MERGE para juntar alterações do BRANCH no MAIN:
> Necessário voltar a MAIN:
$ git checkout main

> Agora sim o comando MERGE:
$ git merge feature/novo_arquivo

# Deletar o BRANCH que acabou de juntar ao MAIN:
$ git branch -d feature/novo_arquivo


 