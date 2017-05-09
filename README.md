# Comandos git-github


*------ Processo de envio ------*

git clone https://github.com/alanandrade/git-github.git
git init
$ git config --global user.name "Alan Andrade"
$ git config --global user.email alan.andradebispo@gmail.com
git status

*------ Adicionando arquivos ------*

git add *
git add nomedoarquivo.formato <!-- Para enviar somente um arquivo -->
git commit -m "Primeiro envio"
git push origin master
		

*------ Processo de Excluir arquivo ------*

git rm -r teste.html
git commit -m "Remover arquivo teste.html"
git push origin master
		

*------ Processo de LOG: ------*

git log
git log -p</li> <!--Traz o log + as alteracoes em cada commit-->
		