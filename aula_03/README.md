# Tutorial de Comandos Básicos do Git


## Identidade:


* git config --global user.name

  Este comando altera globalmente o nome de usuário associado a realização dos commits.

  `git config --global user.name "AndersonAnaya95"`

* git config --global user.email

  Este comando altera globalmente o email associado ao usuário.

  `git config --global user.email andersonanaya.contato@outlook.com`

Para verificar se seus comandos funcionaram, é possível utilizar o `git config --list`. O resultado deve ficar da seguinte maneira:

![git name e email](images/01.PNG.png "git name e email")


## Inicialização:


Todos os comandos abaixo devem ser feitos dentro do diretório do projeto.

* git init

    Este comando inicia o Git no repositório.
    
    `git init`

  * git remote

    Este comando vincula o link do repositório do Github ao nome **origin**.

    `git remote add origin https://github.com/AndersonAnaya95/Teste.git`
    
    ![git init e remote](images/02.PNG "git init e remote")
    
    Na imagem acima, primeiramente foi iniciado o Git no repositório através do `git init` e após essa inicialização, foi indicado o diretório remoto para origem através do `git remote`.
    
  * git clone
  
    Transfere os arquivos do repositório online para a sua máquina.
    
    `git clone https://github.com/AndersonAnaya95/Desafio4Linux.git`
    
    
## Modificação:


* git add

  Este comando, seguido do identificador do arquivo, adiciona o mesmo à fila para a realização do commit.

    * git rm
  
      Este comando seguido do identificador do arquivo remove o mesmo do diretório.
  
    * git commit
  
      Este comando registra uma atividade realizada.
  
    * git push
  
      Este comando faz o upload das alterações para o diretório remoto.
  
      `git push origin master`
  
      O comando acima envia os arquivos para o repositório remoto, com o apelido de **origin** no branch principal.
      
      ![git push](images/03.PNG "git push")
      
      Na imagem acima, após a execução do comando, é apresentado um relatório exibindo o status da operação. No caso desta imagem, o relatório exibe que o push foi realizado com sucesso e mostra a quantidade de alterações.
  
    * git pull
  
      Este comando solicita a atualização do diretório local, puxando as informações do diretório remoto.
      
      Antes da realização do git pull:
      
      ![antes pull](images/antes-pull.png "antes pull")
      
      Depois da utilização do git pull:
      
      ![depois pull](images/depois-pull.png "depois pull")
  
      `git pull origin master`
  
      O comando acima baixa qualquer alteração realizada no repositório remoto, com o apelido de **origin** no branch principal.
      
      ![git pull](images/pull.PNG "git pull")
      
      Na imagem acima é apresentado o status do repositório remoto em relação ao repositório local (quantidade de arquivos diferentes entre os locais) e também é exibida uma notificação sobre a atualização do local.


## Inspeção:


* git status

  Este comando retorna o estado do diretório (exibe se existem arquivos alterados).

    * git log
  
      Exibe os commits realizados.
      
      ![git log](images/git-log.PNG "git log")
      
      A imagem acima exibe os últimos commits realizados de forma abreviada.
      
      O parâmetro `--oneline` é opcional e foi utilizado para reduzir o tamanho da imagem neste tutorial.
      
