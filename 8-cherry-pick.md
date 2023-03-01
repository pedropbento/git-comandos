# Comando CHERRY-PICK
> Comando "cherry-pick" consiste em pegar o commit de outra branch e levar para a branch de feature. Por exemplo: uma correção de bug é feita paralela em um branch hotfix e esse deve ser unificado ao branch feature.

## Criando a BRANCH de HotFix (correção):
$ git checkout -b hotfix

## Confirmar se esta no branch Hotfix:
$ git branch 
  feature/nova-versao
* hotfix
  main

## Após fazer as correções/inclusões no BRANCH HotFix, deverá levar as mudanças para o branch feature/nova-versao com o comando "cherry-pick":

1. [Fazer o commit do branch hotfix]
$ git add .
$ git commit -m "Adicionando as alterações no branch hotfix."

2. [Pegar o hash do comit do branch hotfix que será usado no "cherry-pick"]
$ git log
commit 7fa15e90ad2e5e00a95a2617ba6ee7d695ed1a00 (HEAD -> hotfix)

3. [Ir para branch feature/nova-versao]
$ git checkout feature/nova-versao

4. [Executa o comando "cherry-pick" para puxar as alterações do commit da feature/nova-versao] 
$ git cherry-pick 7fa15e90ad2e5e00a95a2617ba6ee7d695ed1a00

5. [Execute o ADD e o COMMIT na brach feature/nova-versao]
$ git add .
$ git commit -m "Commid das alterações do horfix"

6. [Execute o MERGE do branch feature/nova-versao na MAIN]:
> Mude para o branch MAIN:
$ git checkout main
> Execute MERGE:
git merge feature/novo_arquivo

# Deletar os BRANCHS hotfix e feature/novo_arquivo
$ git branch -d feature/novo_arquivo
$ git branch -d hotfix









