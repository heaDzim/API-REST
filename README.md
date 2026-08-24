# 🏪 API REST — Baozi Store

Projeto desenvolvido para a atividade prática da disciplina de **Desenvolvimento Web Back-End**. A aplicação consiste em uma API REST para controle básico de clientes, produtos e pedidos de uma pequena loja especializada na venda de pãozinho chinês (Baozi).

**Nome:** Marcelo Souza  
**RU:** 5151437

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Java
* **Framework Principal:** Spring Boot
* **Persistência de Dados:** Spring Data JPA
* **Banco de Dados:** MySQL
* **Gerenciador de Dependências:** Maven
* **Arquitetura:** API REST com Padrão MVC
* **Formatos de Dados:** JSON
* **Testes de Endpoints:** Postman

---

## 📁 Estrutura do Projeto

O projeto foi organizado seguindo a arquitetura MVC (Model-View-Controller) do Spring Boot, utilizando a seguinte divisão de pacotes:

```text
src/main/java
└── com.baozistore
    ├── controller
    │   ├── ClienteController.java
    │   ├── ProdutoController.java
    │   └── PedidoController.java
    ├── model
    │   ├── Cliente.java
    │   ├── Produto.java
    │   └── Pedido.java
    └── repository
        ├── ClienteRepository.java
        ├── ProdutoRepository.java
        └── PedidoRepository.java
