## Trababalhado com repositório remoto
> Como trabalhar localmente e subir as alterações para o repositorio remoto (gitHub)

# Crie uma branch localmente para as alterações
$ git checkout -b novaBranch

# Apos alterações faça o ADD e COMMIT:
$ git add .
$ git commit -m "Alterações locais."

# Enviar alterações para GitHub, porém vinculando a uma Branch em Origin Main
$ git push --set-upstream origin novaBranch

