AgroScan API
Descrição do Projeto

O AgroScan API é uma solução desenvolvida em Java utilizando Spring Boot para auxiliar na análise da viabilidade de cultivo em diferentes condições ambientais.
A aplicação permite o cadastro e gerenciamento de usuários, vegetais, solos, climas, corpos celestes, requisitos de cultivo e simulações, fornecendo uma plataforma completa para avaliação de cenários agrícolas.
Além disso, a API utiliza autenticação JWT para garantir segurança no acesso aos recursos e HATEOAS para navegação entre endpoints.

----------------------------------------------------------------------------------------------------------------------------------------
Tecnologias Utilizadas

Java 21
Spring Boot
Spring Data JPA
Spring Security
JWT Authentication
Swagger OpenAPI
HATEOAS
H2 Database
Gradle
Lombok
Funcionalidades
Cadastro de Usuários
Cadastro de Vegetais
Cadastro de Solos
Cadastro de Climas
Cadastro de Corpos Celestes
Cadastro de Requisitos Vegetais
Cadastro de Relatórios de Viabilidade
Simulação de Cultivo
Autenticação com JWT
Documentação automática com Swagger
Tratamento global de exceções
Validação de dados com Bean Validation
Estrutura do Projeto
----------------------------------------------------------------------------------------------------------------------------------------

O projeto foi organizado seguindo a arquitetura em camadas:

Controller
Service
Repository
DTO Request
DTO Response
Mapper
Security
Exception
Model

Essa estrutura facilita a manutenção, escalabilidade e organização da aplicação.

----------------------------------------------------------------------------------------------------------------------------------------
Segurança

A API utiliza autenticação baseada em JSON Web Token (JWT).

Fluxo de autenticação:

O usuário realiza login.
A API gera um token JWT.
O token é enviado nas requisições protegidas.
O Spring Security valida o token e libera o acesso aos endpoints autorizados.

----------------------------------------------------------------------------------------------------------------------------------------
Documentação da API

A documentação dos endpoints é disponibilizada através do Swagger OpenAPI.

Por meio da interface é possível:

Visualizar todos os endpoints
Realizar testes diretamente pelo navegador
Autenticar utilizando JWT
Consultar parâmetros e respostas da API
Modelagem Avançada

----------------------------------------------------------------------------------------------------------------------------------------
O projeto implementa conceitos avançados de persistência:

Herança

Utilização de uma classe base compartilhada entre entidades através de:

@MappedSuperclass
Embedded

Utilização de objeto incorporado através de:

@Embeddable
@Embedded
Chave Composta

Implementação utilizando:

@EmbeddedId
Simulação de Cultivo

A funcionalidade principal da aplicação é a simulação de cultivo.

Através das informações cadastradas é possível avaliar a viabilidade de uma determinada cultura considerando:

Vegetal
Solo
Clima
Corpo Celeste
Condições ambientais

O sistema gera uma classificação de viabilidade e armazena os resultados para futuras consultas.

----------------------------------------------------------------------------------------------------------------------------------------
Tratamento de Exceções

Foi implementado um tratamento global de exceções utilizando:

ResourceNotFoundException
GlobalExceptionHandler

Dessa forma a API retorna respostas padronizadas para erros de validação e recursos não encontrados.

----------------------------------------------------------------------------------------------------------------------------------------
Resultados

O projeto foi desenvolvido com sucesso, atendendo aos requisitos de:

API REST
Persistência de dados
Segurança com JWT
HATEOAS
Swagger
CRUD completo
Validações
Relacionamentos entre entidades
Modelagem avançada
Conclusão

O AgroScan API demonstra a aplicação prática dos conceitos de desenvolvimento de APIs REST utilizando Spring Boot, segurança com JWT, persistência com JPA e boas práticas de arquitetura em camadas.
A solução desenvolvida permite gerenciar informações agrícolas e realizar simulações de cultivo de forma organizada, segura e escalável.
