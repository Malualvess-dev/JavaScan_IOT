# 🌱 AgroScan API

## 🚀 Sobre o Projeto

O AgroScan é uma API REST desenvolvida em Java com Spring Boot para auxiliar na gestão agrícola inteligente através da integração de informações sobre vegetais, solos, clima, usuários, simulações de cultivo e condições de diferentes corpos celestes.

Além da aplicação na agricultura tradicional, o projeto também explora cenários de agricultura espacial, simulando condições de cultivo em ambientes como Marte, contribuindo para pesquisas relacionadas à economia espacial e sustentabilidade futura.

---

## 🎯 Objetivo

Fornecer uma plataforma moderna, segura e escalável para gerenciamento de dados agrícolas, permitindo análises e simulações de viabilidade de cultivo em diferentes ambientes.

---

## 🛠️ Tecnologias Utilizadas

- Java 21
- Spring Boot
- Spring Data JPA
- Spring Security
- JWT (JSON Web Token)
- HATEOAS
- Swagger / OpenAPI
- Gradle
- H2 Database
- Render (Deploy)

---

## 🏗️ Arquitetura

O projeto segue arquitetura em camadas:

```text
Controller
↓
Service
↓
Repository
↓
Banco de Dados
```

Componentes auxiliares:

```text
DTO
Mapper
Security
Exception Handler
```

---

## 🔐 Segurança

A API utiliza autenticação JWT para proteção dos endpoints.

Fluxo:

```text
Login
↓
Geração do Token JWT
↓
Authorize no Swagger
↓
Acesso aos endpoints protegidos
```

---

## 📚 Documentação da API

Swagger/OpenAPI:

👉 https://javascan-iot-1.onrender.com/swagger-ui/index.html#/

---

## 🌐 Deploy

Aplicação hospedada no Render:

👉 https://javascan-iot-1.onrender.com

---

## 🎥 Vídeo de Apresentação

YouTube:

👉 https://youtu.be/T6WK75eiOZU?si=ctrHacP2BOBkL68b

---

## ▶️ Como Executar Localmente

### Clonar o repositório

```bash
git clone https://github.com/Malualvess-dev/JavaScan_IOT.git
```

### Entrar na pasta

```bash
cd JavaScan_IOT
```

### Executar a aplicação

```bash
gradlew bootRun
```

ou

```bash
./gradlew bootRun
```

### Gerar arquivo JAR

```bash
gradlew bootJar
```

Arquivo gerado:

```text
build/libs/agroscan-api-0.0.1-SNAPSHOT.jar
```

Executar:

```bash
java -jar build/libs/agroscan-api-0.0.1-SNAPSHOT.jar
```

---

## 📋 Principais Funcionalidades

- Cadastro de Usuários
- Cadastro de Vegetais
- Cadastro de Solos
- Cadastro de Climas
- Cadastro de Corpos Celestes
- Simulações de Cultivo
- Autenticação JWT
- Documentação Swagger
- Navegação HATEOAS
- Deploy em Ambiente Cloud

---

## 📊 Recursos Implementados

✅ API RESTful

✅ Spring Security

✅ JWT Authentication

✅ Swagger/OpenAPI

✅ HATEOAS

✅ DTOs e Mappers

✅ Tratamento Global de Exceções

✅ Modelagem JPA

✅ Herança

✅ Embedded

✅ Chave Composta

✅ Deploy em Produção

---

## 📌 Informações para Avaliação

- Projeto desenvolvido utilizando Java 21 e Spring Boot.
- API documentada com Swagger/OpenAPI.
- Endpoints protegidos por JWT.
- Deploy realizado em ambiente cloud utilizando Render.
- Demonstração completa disponível em vídeo.
- Documentação centralizada neste README conforme requisitos da disciplina.

---

## 🔗 Links do Projeto

### GitHub
https://github.com/Malualvess-dev/JavaScan_IOT

### Deploy
https://javascan-iot-1.onrender.com

### Swagger
https://javascan-iot-1.onrender.com/swagger-ui/index.html#/

### Vídeo
https://youtu.be/T6WK75eiOZU?si=ctrHacP2BOBkL68b
