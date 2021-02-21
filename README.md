# HELLO-WORDD
Tentando aprender 
create database if not exists fazenda_bd; 
use fazenda_bd;

create table if not exists funcionario(
cod_func int not null auto_increment,
nome_func varchar (30),
cpf_func int (11),
data_nasc date,
setor_func varchar (20),
primary key(cod_func))
