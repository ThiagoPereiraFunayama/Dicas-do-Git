# Dicas-do-Git

Nesse repositório vai conter dicas do Git.

 
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original-wordmark.svg" width="100px"/>

## O que é o Git.

### Git é um sistema de controle de versão distribuído (DVCS), projetado para lidar eficientemente com projetos de qualquer tamanho. Ele foi desenvolvido por Linus Torvalds em 2005 para gerenciar o desenvolvimento do kernel do Linux. O Git permite que várias pessoas trabalhem em um projeto simultaneamente, rastreando as mudanças em cada parte do código ao longo do tempo.

### Em termos simples, o Git permite que você mantenha um histórico de alterações em seu código, facilitando a colaboração em equipe e o gerenciamento de projetos. Cada contribuição é registrada como um "commit", que contém uma descrição da alteração e uma referência única (hash).

## Vamos começar instalando o git no Linux.

` sudo apt install git` 

## Depois de instalado vamos ver a versão que está no seu computador.

` git --version `    

# O config

 `git config`  É o comando utilizado para configurar o Git, permitindo ajustar diversas opções e comportamento.

## Definindo nome nos commits de forma Global.

`git config --global user.name #Seu Nome#`

## Definindo email nos commits de forma Global.

`git config --global user.mail #Seu Email#`

## Visualizando a configuração do seu Git.

`git config --list`

# Criando o Repositório. 

## Inicializando um repositório Git.

`git init`

## Adicionando um repositório remoto.

`git remote add origin`

# O commit.

## Colocando o comentario.

`git commit -m #Comentario#`

## Branch

`git branch -M main` por padrão colocar o main.

`git checkout #Nome do branch#`  Trocar de branch.

`git fetch` Obter alterações do repositório remoto.

# O Push

`git push -u origin #Nome da branch#`

### merge mescla as branchs com a atual.

`git merge #Nome da branch#`

# O rm

## o comando rm serve para remover algo.

`git rm #arquivo#` aqui é o arquivo que será removido.

`git rm -r #pasta#` aqui será a pasta que vai ser removida.




