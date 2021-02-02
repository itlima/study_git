Pré-requisitos

- Instalação do git em sua máquina.

# Conceitos

## Controle de versão

- Uma técnica que auxilia a gerenciar o código-fonte de uma aplicação;
- Registrando todas a modificações de código, podendo também reverter essas alterações;
- Cria versões de um software em diferentes estágios, podendo alterar de forma simples entre elas;
- Cada membro da equipe pode trabalhar em uma versõa diferente.

## Git

- O sistem de controle de versão mais utilizado do mundo atualmente;
- O git é baseado em repositório, que contêm todas as versões do código e também as versões de cada desenvolvedor (branch);
- Todos os objetos do git são protegidos como criptografia para evitar alterações indevidas e maliciosas;
- O git é um projeto de código aberto;
- O git não é o github, bitbucket ou gitlab, ele é uma ferramenta para versionamento de código, os demais são servidores para hospedar os repositórios dos projetos.

## Kit básico de sobrevivencia do git

### Repositório

- Onde o código será armazenado;
- Na maioria das vezes cada projeto possui um repositório;
- O repositóirio pode ir para servidores que são especializado em gerenciar repositórios, como: Github, Bitbucket e Gitlab;
- Cada um dos desenvolvedores do time pode baixar o repositório e criar versões deferentes em sua máquina.

Para criar um repositório é utilizado o comando `git init`, desta maneira o git vai criar os arquivos necessário para inicializá-lo, podendo ser encontrados na pasta oculta `.git`. Após a execução deste comando, o diretório é reconhecido pelo git como um projeto, podendo responder a diversos comando incluidos no binário do git.

Execute o seguinte comando dentro da pasta desejada para criar um repositório.

```
$ git init 
Initialized empty Git repository in /home/r2d2/courses/git/.git/
```

Execute o seguinte comando para verificar se o repositório foi inicializado

```
$ git status
On branch master

No commits yet

nothing added to commit but untracked files present (use "git add" to track)
```

## Enviando repositórios para o Github

Os repositório podem ser enviados para o Github, é necessário primeiro criar o projeto, inicializar ele em sua máquina (`git init`), sincronizar e enviar ao Github. Esse fluxo é realizado uma única vez por projeto. 

Acesse sua conta no Github e crie um repositório com o nome que desejar.

![](/home/r2d2/courses/git/img/01_create_a_new_repository.png)

Crie uma pasta em sua máquina e entre nela.

```bash
$ mkdir git
$ cd git 
```

Inicialize o repositório 

```bash

```

Adicione algum arquivo para o repositório

```bash
echo "# TUTORIAL GIT" >> README.md
$ git init 
$ git add README.md
$ git commit -m "Criando arquivo de README.md"
$ git branch -M master
$ git remove add origin 
```

Adicione as mudanças realizadas no seu projeto.

Envie as mudanças adicionadas ao seu projeto local para o seu projeto existente nos servidores do Github.

```

```

Crie uma branch nomada como master.

git remove 

## Github

Um serviço para gerenciar repositório, gratuito e amplamente utilizado, é possível enviar projetos para o Github e disponibilizá-lo para outros desenvolvedores. No Github é possível criar projetos publicos e privados de maneira gratuita. 





















