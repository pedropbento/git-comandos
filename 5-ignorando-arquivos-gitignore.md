# CONFIGURAÇÃO DO GITIGNORE
> Ignorando arquivos no commit.

## Criar o arquivo .gitignore e nele incluir pastas, extenções ou arquivos que serão ignorados no GIT STATUS e COMMIT:
# EXEMPLO:
	.gitignore
	bin/
	*.log
	*.exe
	*.dll
	*/bin/ 
# O arquivo .gitignore deve ser feito COMMIT:	
$ git add .gitignore
$ git commit -m "Inclusão do arquivo .gitignore"
