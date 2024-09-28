programa - visual studio code, https://code.visualstudio.com/
extensoes = code runner
gitgraph = visualizador de fluxo de git

liguagens
javascript - Frontend, backend, aplicativos mobile 
Python - IAI, Data science

java - Backend - fortemente tipada
C# - Backaend, Games, Unity - fortemente tipada
C++ Versátil, Game Unreal -fortemente tipada


Forum de dúvidas:
https://stackoverflow.com/


GIT
https://git-scm.com/downloads/win

subir para o github:
Instalar o git para o sistema operacional  unica vez por computador

git init - para inicar o git na primeira vez unica vez

inseir dados do seu usuário
git config --global user.email "you@example.com"
git config --global user.name "Your Name"

cria no github um repositório
no terminal do projeto
git remote add origin "URL DO PROJETO NO GIT"
git add -A -  adiciona para o git rastrear
git comit -m "QUALQUER MENSAGEM"
git push -u origin master - uma só

para baixar o projeto:
git clone {GIT_REPO_URL}
git checkout -b {BRANCH_NAME}

para atualizar e salvar o projeto:
git add -A
git commt -m "mensagem"
git push


Explicação do Github
…or create a new repository on the command line
echo "# aula" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jonathandanilo222/aula.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/jonathandanilo222/aula.git
git branch -M main
git push -u origin main

git commit -m "{MESSAGE}"
