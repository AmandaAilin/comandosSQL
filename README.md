# Comandos - Structured Query Language (SQL)
<p>Neste artigo você aprenderá os principais comando do SQL.</p>

### Que é SQL?
<p>Então SQL (Structured Query Language) é uma linguagem de programação usada para gerenciar e manipular bancos de dados relacionais. Ela fornece uma maneira padronizada de realizar diversas operações em bancos de dados, como consultar, inserir, atualizar e excluir dados.</p>
<p>O SQL é amplamente utilizado em sistemas de gerenciamento de bancos de dados (SGBDs) para interagir com o banco de dados e executar várias tarefas. Com o SQL, é possível criar e modificar esquemas de banco de dados, definir tabelas e colunas, estabelecer relacionamentos entre tabelas, realizar consultas complexas para recuperar informações específicas, atualizar registros existentes e inserir novos dados.</p>

## Índice de comandos
* [](#)
* [](#)
* [](#)


## Comandos para iniciar:

~~~sql
  show databases;
~~~
<p>Veamos la explicação por partes deste comando:</p>

*  **show** -> comando para apresentação.

*  **databases** -> banco de dados existentes.

* **;**  -> este ponto e virgula determina o final do comando.

</br>

##  Acessando um Banco de Dados:

~~~sql
  use Faculdade;
~~~

</br>

## Descobrindo o Banco de Dados que você está conectado:

~~~sql
  select database();
~~~
</br>

## Apresentando as tabelas existentes dentro de um Banco de Dados:

~~~sql
  show tables;
~~~

</br>

## Criando um Banco de Dados:

~~~sql
  create database Faculdade;
~~~

> create                  Comando de criação.

>  database             Declaração que será criado um Banco de Dados.

>  Faculdade            Nome do Banco de Dados. 

> ; Ponto-e-vírgula, determina o final do comando.

<p> :warning: Vale salientar que o nome escolhido não deve pertencer a um Banco de Dados
existente, nem ser uma palavra reservada.</p>

</br>

<p>Inclusive podemos realizar uma pré-verificação da existência de um Banco de Dados com o mesmo nome. Para isso, basta utilizar o comando if not exists (se não existir).</p>

~~~sql
  create database [if not exists] Faculdade;
  
  -- Essa query somente criará o Banco de Dados se o mesmo não existir.
~~~



