Virtual Shop API
A Virtual Shop API é uma API RESTful desenvolvida em Java utilizando o Spring Boot. Ela permite realizar operações CRUD (Criar, Ler, Atualizar, Deletar) em produtos de uma loja virtual. A API suporta a persistência dos dados no banco de dados relacional.

Funcionalidades
POST /product - Criar um novo produto
GET /product - Listar todos os produtos
GET /product/{id} - Consultar um produto específico
PUT /product/{id} - Atualizar um produto existente
DELETE /product/{id} - Excluir um produto
Tecnologias Utilizadas
Java (JDK 11 ou superior)
Spring Boot 2.x
Spring Data JPA (para comunicação com o banco de dados)
H2 Database (banco de dados em memória para desenvolvimento)
Spring Validation (para validação de entradas)
JUnit 5 (para testes)
Maven (gerenciador de dependências e build)
Pré-requisitos
Java 11+ instalado.
Maven para gerenciar dependências.
IDE (como IntelliJ IDEA ou Eclipse) para desenvolvimento.
