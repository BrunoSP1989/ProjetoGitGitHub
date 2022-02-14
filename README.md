Primeiro Repositório no Git/GitHub

Primeiro passso

Voçê entrará nesse link -> https://git-scm.com/.
e efetuara as instalações de acordo com o curso Introdução
do Git e GitHub da DIO (Digital Innovation One).

Segundo Passo será configurar seu GitHub no git,
crie uma pasta com nome Workspace em seu diretorio no seu
HD.
Após isso vc clicará na pasta Workspace com botão direito
do mouse e cliacará em Git Bash Here e abrirá uma janela 
no terminal Git.

crie um arquivo na pasta Workspace com nome Readme.md 
(necessário o arquivo seja extensão .md), após isso
volte no terminal Git e siga esses passo a seguir:

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/seuusuario/nomedorepositório.git 
(após ter criado o seu repositório no GitHub.com, não
se esqueça de deixar seu repositório público).
git push -u origin main

após isso abrirá uma página no GitHub para vc poder sincronizar seu dados
do repositório local(Git) para o seu repositório remoto (GitHub).
Após isso seu primeiro projeto estará publicado no GitHub.