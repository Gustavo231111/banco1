# banco1
````sql 
require 'redcarpet'
markdown = Redcarpet.new("Hello world")
puts markdown.to.html
````
````
-- criando um novo banco de dados
create database trabalho;
````
````
-- usar banco 
use trabalho;
````
````sql
-- criar tabela ex 1
create table cliente(
idcliente int primary key,
nomecliente varchar(100),
emailcliente varchar(100),
datanascimento date,
telefonecliente varchar(15)
);
````
````sql
-- criar tabela ex 2
create table produto(
idproduto int primary key,
nomeproduto varchar(100),
precoproduto decimal(8,2)
);
````


````sql
-- criar tabela ex 3
create table faturas(
idfatura int primary key,
datacriacao date,
valorfatura decimal(10,2)
);
````
````sql
-- criar tabela ex 1
create table funcionarios(
id int primary key,
nome varchar(100),
sobrenome varchar(100),
salario int
);
````
````sql
-- criar coluna ex 2
alter table funcionarios add datanascimento date;
````
````sql
--criar tabela ex 3
create table departamentos (
codigo int  primary key
nome varchar (100)
);
````
````sql
--criar coluna ex 4
alter table funcionarios add IDDepartamento int
````
````sql
--criar tabela ex 5
-- criando tabela projeto
create table projeto (
codigo int primary key,
nome varchar (100)
);
````
````sql
--criar tabela ex 6
create table alocacoes (
codigo primary key 
); 6
````
````sql
--substituir ex 7
alter table funcionarios rename column sobrenome to apelido;
````

````sql
--criar tabela ex 8
create table clientes (
id_cliente int primary key,
nome_cliente varchar (100),email_cliente varchar(150),data_nascimento date,);
````
````sql
--coluna ex 9
alter table projeto add IDCliente varchar (100);
````
````sql
--criar tabela ex 10
create table endereco(
codigo primary key
rua varchar(50)
cidade varchar(50)
cep  int 
);
````
`````sql
--coluna ex 11
alter table funcionarios add IdEndereco varchar (100);
``````
````sql
--renomeando a coluna ex 12
alter table clientes rename column nome_cliente to NomeEmpresa;
````
````sql
--criando uma tabela ex 13
create table pedidos(
id primary key,
Datapedido date
);

`````
````sql
--coluna ex 14
alter table pedidos add IdCliente int;

````
````sql
--Criando uma tabela ex 15
create table intensPedido(
id primary key,
IdPedido int,
IdProduto int,
);
````
`````sql
--Criando uma tabela ex 16
create table produtos(
id primary key,
NomeProduto varchar(100),
quantidadeProduto int,
valorProduto int,
);

``````
````sql
--Renomeando ex 17
alter table produto rename column nome_produto to DescricaoProduto; 
````
````SQL
--Criando uma tabela ex 18]
create table Estoques(
    id primary key,
    Quantidade int,
);

````
````sql
--Criando uma coluna ex 19
alter table Estoques add IdProduto int;
````
````SQL
--Criando uma tabela ex 20
create table Vendas(
    id primary key,
    Datavenda date,
);

````
````sql
--Criando uma coluna ex 21
alter table Vendas add IdCliente int;
````














