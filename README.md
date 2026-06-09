# 🌱 AgroScan API

Sistema desenvolvido em Java com Spring Boot para gerenciamento e simulação de cultivo agrícola em diferentes condições ambientais.

---

## 🚀 Tecnologias Utilizadas

* ☕ Java 21
* 🌱 Spring Boot
* 🗄️ Spring Data JPA
* 🔐 Spring Security
* 🎫 JWT Authentication
* 📖 Swagger OpenAPI
* 🔗 HATEOAS
* 🛢️ H2 Database
* ⚙️ Gradle
* 📦 Lombok

---

## 📋 Funcionalidades

### 👤 Usuários

* Cadastro de usuários
* Consulta de usuários
* Atualização de usuários
* Exclusão de usuários

### 🌿 Vegetais

* Cadastro de vegetais
* Consulta de vegetais
* Atualização de vegetais
* Exclusão de vegetais

### 🌎 Solos

* Cadastro de solos
* Consulta de solos
* Atualização de solos
* Exclusão de solos

### ☁️ Climas

* Cadastro de climas
* Consulta de climas
* Atualização de climas
* Exclusão de climas

### 🪐 Corpos Celestes

* Cadastro de corpos celestes
* Consulta de corpos celestes
* Atualização de corpos celestes
* Exclusão de corpos celestes

### 📊 Simulações

* Simulação de cultivo
* Cálculo de viabilidade
* Armazenamento dos resultados
* Histórico de análises

### 🔒 Segurança

* Login autenticado
* Geração de Token JWT
* Rotas protegidas
* Integração com Swagger Authorize

---

## 🏗️ Arquitetura do Projeto

O projeto foi desenvolvido seguindo o padrão em camadas:

```text
controller
service
repository
dto
mapper
security
exception
model
```

---

## 📖 Documentação Swagger

A documentação da API pode ser acessada através do Swagger:

```text
http://localhost:8080/swagger-ui/index.html
```

Através do Swagger é possível:

* Testar endpoints
* Realizar autenticação JWT
* Consultar parâmetros
* Visualizar respostas da API

---

## 🔐 Autenticação JWT

Fluxo de autenticação:

1. Realizar login
2. Receber token JWT
3. Autorizar no Swagger
4. Consumir endpoints protegidos

---

## 🔗 HATEOAS

A API implementa HATEOAS para navegação entre recursos, retornando links relacionados juntamente com os dados da resposta.

---

## 🧬 Modelagem Avançada

O projeto implementa os seguintes conceitos avançados de persistência:

### 🏛️ Herança

* `@MappedSuperclass`

### 📦 Embedded

* `@Embeddable`
* `@Embedded`

### 🆔 Chave Composta

* `@EmbeddedId`

---

## 🛠️ Tratamento de Exceções

Tratamento global implementado utilizando:

* ResourceNotFoundException
* GlobalExceptionHandler

Garantindo respostas padronizadas para erros e validações.

---

## 🎯 Objetivo do Projeto

Desenvolver uma API REST completa para gerenciamento e simulação de cenários agrícolas, permitindo a análise de viabilidade de cultivo com base em informações ambientais, climáticas e estruturais.

---

## ✅ Status do Projeto

* ✅ CRUD Completo
* ✅ DTO Request/Response
* ✅ Validation
* ✅ Mapper
* ✅ Service
* ✅ Repository
* ✅ Swagger
* ✅ JWT
* ✅ HATEOAS
* ✅ Exception Handler
* ✅ Herança
* ✅ Embedded
* ✅ Chave Composta
* ✅ Simulação de Cultivo
* ✅ Spring Security

---

## 👨‍💻 Desenvolvido com Java + Spring Boot
