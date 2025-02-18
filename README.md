# Projeto Spring com JPA e Hibernate

Este projeto é uma implementação de um sistema de pedidos utilizando Spring Boot, JPA (Java Persistence API) e Hibernate. O objetivo é demonstrar como estruturar um banco de dados relacional e realizar operações de persistência utilizando essas tecnologias.

## 📌 Tecnologias Utilizadas

Java 17

Spring Boot

JPA / Hibernate

H2 Database (banco de dados em memória)

Maven


## 🔹 Entidades Principais

User: Representa um usuário do sistema, contendo informações como nome, e-mail, telefone, data de nascimento, senha e funções.

Order: Representa um pedido realizado por um usuário, contendo informações como data do pedido e status.

Product: Representa um produto disponível para compra, com atributos como nome, descrição, preço e URL da imagem.

Category: Representa uma categoria de produtos.

OrderItem: Representa um item dentro de um pedido, relacionando um pedido a um produto, com quantidade e preço.

Payment: Representa um pagamento relacionado a um pedido.

OrderStatus (Enum): Define os possíveis status de um pedido: WAITING_PAYMENT, PAID, SHIPPED, DELIVERED, CANCELED.

## 🎯 Funcionalidades

✅ Cadastro e listagem de usuários
✅ Cadastro e listagem de pedidos
✅ Cadastro e listagem de produtos
✅ Relacionamento entre produtos e categorias
✅ Registro de pagamentos para pedidos

## 🛠️ Configuração e Execução

Clone o repositório

git clone https://github.com/gustavolucenadev/java_spring_orm

Acesse o diretório do projeto

cd seu-repositorio

Execute o projeto

mvn spring-boot:run

Acesse o banco de dados H2

URL: http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:testdb

Usuário: sa

Senha: (vazio)


