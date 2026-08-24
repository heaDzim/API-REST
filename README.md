API REST - Baozi Store

Projeto desenvolvido para a atividade prática da disciplina de Desenvolvimento Web Back-End, utilizando Java, Spring Boot, Spring Data JPA, MySQL e Postman.

A aplicação consiste em uma API REST para controle básico de clientes, produtos e pedidos de uma pequena loja especializada na venda de pãozinho chinês.

Nome: Marcelo Souza RU 5151437

Tecnologias utilizadas
- Java, Spring Boot, Spring Data JPA, MySQL, Maven, Postman, JSON, API REST com Arquitetura MVC.

Estrutura do projeto

O projeto foi organizado seguindo a arquitetura MVC do Spring Boot, utilizando os seguintes packages:

src/main/java
-com.baozistore
  -controller
  ClienteController.java
  ProdutoController.java
  PedidoController.java
 
   -model
   Cliente.java
   Produto.java
   Pedido.java
   
   -repository
   ClienteRepository.java
   ProdutoRepository.java
   PedidoRepository.java
