# Desafio 4Linux - Treinamento

## Requisitos

Para realizar o desafio você vai precisar:

1. Ter o [git](https://git-scm.com/download/win) instalado em sua máquina
2. Utilizar algum editor de markdown como o [stackedit](https://stackedit.io/)

## Preparação

Você deverá realizar um clone deste repositório para sua máquina para iniciar o desafio.

## Desafio

O cenário do desafio é o versionamento de um tutorial. O tutorial está dividido em 3 aulas, em uma estrutura fixa: 

``` bash
.
├── aula_01
│   └── README.md
├── aula_02
│   └── Tarefa_02.docx
├── aula_03
│   └── README.md
└── README.md

```

Em cada pasta de aula contém um arquivo chamado _README.md_. Estes arquivos serão utilizados para armazenar o conteúdo de cada aula, e deverão estar no formato (Markdown)[https://www.markdownguide.org/basic-syntax/]. 

Você deverá realizar as tarefas à seguir utilizando este repositório como base.

### Tarefa 1 

Você deverá escrever um tutorial de instalação do _git_ no arquivo README.md da pasta aula\_01 do repositório respeitando o formato _markdown_.

O tutorial deverá conter um passo a passo com imagens de como realizar o download e instalação da aplicação. Você pode escolher o sistema operacional de sua preferência para utilizar no tutorial.

As imagens utilizadas nesta primeira aula deverão ser armazenadas em um pasta dentro do diretório aula\_01 chamada `images` e deverão ser referenciadas no arquivo da aula.


### Tarefa 2

Na pasta da aula\_02 temos um arquivo de texto que não está formato _markdown_. Você deverá reescrever o conteúdo do arquivo em um novo arquivo chamado `README.md` já no formato _markdown_. 

Ao final desta tarefa, a estrutura de arquivos e diretórios deverão estar da seguinte maneira:

```bash
.
├── aula_01
│   ├── images
│   └── README.md
├── aula_02
│   ├── images
│   ├── README.md
│   └── Tarefa_02.docx
├── aula_03
│   └── README.md
└── README.md

```

### Tarefa 3

Você deverá escrever um tutorial de comandos básicos do _git_. O tutorial deverá estar na pasta `aula_03`, como conteúdo do arquivo `README.md`. Assim como na primeira tarefa, será necessário escrever um passo a passo e utilizar imagens.

Você deverá explicar no tutorial os significados e demonstrar com exemplos, os usos dos seguintes comandos:

- Identidade:
	- git config --global user.name 
	- git config --global user.email
- Inicialização 
  - git init
	- git remote 
	- git clone
- Modificação
  - git add
	- git rm
	- git commit
	- git push
	- git pull
- Inspeção
  - git status
	- git log


## Entrega do desafio

Ao final da realização do desafio você pode:

1. Criar um repositório em alguma plataforma como _github_ ou _gitlab_; ou
2. Compactar a pasta com os arquivos em formatos zip e encaminhar por e-mail;




