# 📚 Fórum Hub API

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-green?style=for-the-badge"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-blue"/>
  <img src="https://img.shields.io/badge/Spring_Boot-3.x-blue"/>
  <img src="https://img.shields.io/badge/Maven-4.0.0-blue"/>
  <img src="https://img.shields.io/badge/PostgreSQL-Database-blue"/>
  <img src="https://img.shields.io/badge/JWT-Autenticação-blue"/>
</p>

---

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte do programa **Oracle Next Education (ONE)** em parceria com a Alura, com foco na especialização em Backend.

A aplicação consiste em uma **API REST para gerenciamento de um fórum**, permitindo o controle de tópicos, cursos e usuários, aplicando boas práticas de desenvolvimento com Spring Boot, autenticação com JWT e versionamento de banco de dados com Flyway.

---

## 🚀 Funcionalidades

- ✅ CRUD de Tópicos  
- ✅ CRUD de Cursos  
- ✅ CRUD de Usuários  
- 🔐 Autenticação e autorização com JWT  
- 📄 Documentação automática com Swagger/OpenAPI  
- 🗃 Persistência com PostgreSQL  
- 🔄 Versionamento de banco com Flyway  
- ⚠️ Tratamento adequado de códigos HTTP  

---

## 🛠 Tecnologias Utilizadas

- Java 17  
- Spring Boot  
- Spring Security  
- Spring Data JPA  
- PostgreSQL  
- Flyway Migration  
- Maven  
- Lombok  
- SpringDoc OpenAPI  
- JWT  

---

## 📂 Como Executar o Projeto

### 1️⃣ Clonar o repositório

```bash
git clone <URL_DO_SEU_REPOSITORIO>

2️⃣ Configurar variáveis de ambiente

Configure no application.properties:
DB_HOST=
DB_NAME=
DB_USER=
DB_PASSWORD=
JWT_SECRET=

3️⃣ Criar o banco de dados

Crie o banco no PostgreSQL com o mesmo nome definido nas configurações.

4️⃣ Executar a aplicação

Execute a classe:
ForumHubApplication

5️⃣ Acessar documentação
http://localhost:8080/swagger-ui.html

## 🔐 Autenticação

A API utiliza autenticação baseada em Token JWT.  
É necessário realizar login para obter o token e utilizá-lo nas requisições protegidas.


## 🎯 Objetivo do Projeto

Este projeto demonstra:

- Estruturação de API REST seguindo boas práticas  
- Implementação de segurança com Spring Security  
- Organização em camadas (Controller, Service, Repository)  
- Tratamento de exceções  
- Versionamento de banco de dados  
- Documentação automatizada da API  

## 📎 Requisitos

- Java 17+
- Maven
- PostgreSQL

---

---

---

## 👨‍💻 Autor

**Marcos Rafael Alves** QA | Java | Spring Boot | APIs REST | Segurança com JWT  



