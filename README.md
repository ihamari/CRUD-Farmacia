# 🏥 Projeto Farmácia - Java Spring

Este é um projeto simples de API REST para uma farmácia, desenvolvido com **Java** e **Spring Boot**.  
A estrutura segue o padrão MVC com as camadas: **Model**, **Repository** e **Controller**.

## 🔧 Tecnologias Utilizadas

- Java 17+
- Spring Boot
- Spring Web
- Spring Data JPA
- Banco de Dados Relacional (MySQL)
- Insomnia (Testes)

## 🗂️ Estrutura do Projeto

- `model` → Contém as entidades `Produto` e `Categoria`
- `repository` → Interfaces que estendem `JpaRepository` para acessar o banco de dados
- `controller` → Endpoints REST para manipular os dados das entidades

## 📦 Entidades

### 🧴 Produto

- `id`: Long
- `nome`: String
- `preco`: Double
- `estoque`: Integer
- `categoria`: Categoria

### 🗃️ Categoria

- `id`: Long
- `nome`: String
- `descricao`: String
