﻿# Projeto-final-SENAC
Esse é o projeto de finalização do curso de Desenvolvimento Web - Back End do SENAC Recife.
Nesse repósitorio consta o desenvolvimento de um sistema de consulta, adição e modificação de livros. Similar a de uma Biblioteca.
A primeira pasta, node_modules, serve para armazenar os módulos node necessários para rodar a aplicação. Dentre eles, o express, que cria as rotas da aplicação e o Mongoose que faz a conexão do app com o banco de dados nâo relacional MongoDB.
Na segunda pasta, src, consta todas as funções que são necessários para rodar o sistema de uma Biblioteca. 
A primeira pasta sa src é a Controllers que controla a aplicação. Nela foi desenvolvido as principais funções do app. Como inserir, buscar, deletar e alterar, sendo necessário passar parâmetros do livro, de acordo com o que você deseja fazer.
Outra pasta dentro da src é a db que possui o arquivo de conexão com o banco de dados MongoDB (ATLAS VERSION). 
A terceira pasta da src é a de Models que possui o modelo do Schema de um livro e seus parametros dentro(Id, ISBN, Titulo, Genero, Editora, Autor).
E a quarta pasta da src possui as rotas da aplicação sendo a primeira a Pagina Inicial, a Segunda o Endpoint de consulta de todos os livros no banco. A terceira é o endpoint de Busca de um livro pelo seu ID. A quarta para cadastrar um novo livro. A quinta para atualizar o casastro de um livro. E a ultima para deletar um livro do banco.
O ultimo arquivo .js é o do aplicativo. Que importa todas funções detalhadas acima e inicia o banco de dados em um porta local. Finalizando o processo de Back End da aplicação.
