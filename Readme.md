### Git Course

Este é um repositório teste para ensinar como o Git funciona.

Saiba mais em [kluster Tecnologia](http://www.kluster.com.br)


Melhorando no git

<<<<<<< HEAD
enviando novidades 

modificado do branch master
=======
enviando novidades

modificação na branch testing
>>>>>>> testin g

# Comandos Git

Git init // inicializa o repositorio

Git config user.name // seta o nome de usuario

Git config user.email // seta o email do usuario

Git config —list // lista todas as configurações do git

Git status // serve pra reportar o repositorio

# Comandos Git Log

Git log // mostra todo log dos commits feitos

Git log —author=”fulano” // mostra todos os commits feito por fulano

Git shortlog // mostra os autores em ordem alfabética , a quantidade e quais commits foram

Git shortlog -sn // mostra a quantidade de commits por nome

Git log —graph // mostra o grafico de evolução dos commits

Git show <HASH> // mostra detalhes do que foi modificado no commit 

Git diff // Mostra o que foi modificado

Git diff —name-only // mostra a lista dos arquivos modificados

Git reset HEAD <ARQUIVO-MODIFICADO> // retira os arquivos modificados da stage

Git checkout <ARQUIVO-MODIFICADO> // desfaz as modificações no arquivo

Git reset —soft —mixed —hard  //  soft retorna o arquivo pra stage, mixed volta pra modified, hard volta todas as modificações 

Git Branch (git checkout -b <NOME_BRANCH> // cria ramificações do projeto

Git branch -D <NOME_BRANCH> // apaga o branch

Git merge // juntando as modificações feita em branchs diferentes

Git stash // guarda a modificação do arquivo sem marcar como modified, vc pode usar o arquivo modificado depois usando o comando git stash apply | clear 

Git Alias // cria atalhos para comandos do git (git config —global alias.<NOME_do_ALIAS> COMANDO ABREVIADO (ps:status)

Git revert // revert as modificação do commit sem perder o histórico, diferente do reset


git merge use para pull requests, usar para fazer união de contribuições no final do projeto


# Git Reabase

Rebase para usar durante desenvolvimento do projeto





# Ciclo de vida do Git




Apagando Tags & Branchs

Git tag -d <nome>
Git branch -d <nome>

git push origin :numero_tag
Git push origin :nome_branch



