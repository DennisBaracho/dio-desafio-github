# O que é commit, pull e push?
São operações essenciais para colaboração versionamente de código, os três são comandos presentes no git.

## Commit 
O commit é uma "foto" do seu projeto em determinado momento, exibindo as alterações realizadas, que ficam contidas no histórico de commits. 

Para fazer um commit, utiliza-se o seguinte comando: 
* git commit -m "Sua mensagem de commit aqui"

## Pull
O pull é utilizado para obter as alterações mais recentes do repositório remoto para o repositório local. Com ele, é possível se manter atualizado e trabalhar juntamente à equipe.

Para fazer um pull, utiliza-se o seguinte comando:
* git pull origin nome-do-seu-branch

## Push
O push é utilizado para enviar seus commits para o repositório remoto, oficializando as alterações no código para os outros colaboradores.

* git push origin nome-do-seu-branch

_Neste comando, "origin" representa o nome do repositório remoto padrão (o qual você clonou ou com o qual você inicializou seu repositório local), e "nome-do-seu-branch" é o nome do branch no qual você está trabalhando localmente._

## Checkout
Já vai pra que existir

## Checkout -b
Cria a branch e já troca para ela.
