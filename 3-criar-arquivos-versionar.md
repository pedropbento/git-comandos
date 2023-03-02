# Criar arquivos no repositório e versionando.
> Crie o repositório git local e fazer o commit.

## Verificar conteúdo pastas
$ ls

## Verificar STATUS do repositório (modificações):
$ git status
> Untracked files: (mostra as modificações que precisam ser add ao repositório)

## Adicionar todos arquivos ao repositório (ponto no final do comando):
$ git add .

## Adicionar somente um arquivo:
$ git add README.md

## Após o "git add ." consulte novamente o STATUS:
$ git status
> Changes to be committed: (mostra os arquivos prontos para commit)

## (Dica) Se "Changes to be committed" pode remover os arquivos para commit (state area) com o comando:
$ git reset

# Commit dos arquivos:
$ git commit -m "inserir um comentário significativo"





