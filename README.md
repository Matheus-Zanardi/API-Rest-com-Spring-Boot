📌 API Rest com Spring Boot - Projeto Voll.med

Este repositório contém o projeto desenvolvido durante o curso da Alura, com foco na construção de uma API RESTful utilizando Java com Spring Boot. O sistema simula funcionalidades de uma clínica médica, como o cadastro, listagem, atualização e exclusão de médicos e pacientes.
🚀 Tecnologias utilizadas

    Java 17

    Spring Boot 3.4.4

    Spring Data JPA

    Flyway (versionamento de banco de dados)

    MySQL 8.0

    Insomnia (testes de requisições HTTP)

    Maven

    Lombok

💾 Banco de dados

A aplicação está conectada a um banco MySQL local, configurado via application.properties. As migrations são realizadas automaticamente com Flyway.

🛠 Funcionalidades implementadas

Cadastro de médicos

Listagem paginada de médicos

Atualização de dados de médicos

Exclusão lógica (soft delete)

Validações com Bean Validation

    Documentação clara e organização em camadas

🧪 Testes de API

Todos os endpoints foram testados usando o Insomnia, com as operações principais:

    POST /medicos

    GET /medicos

    PUT /medicos

    DELETE /medicos/{id}


📦 Como rodar o projeto localmente

Clone o repositório:
git clone https://github.com/seu-usuario/seu-repositorio.git

Crie o banco de dados no MySQL:

    CREATE DATABASE vollmed_api;

Configure o application.properties com suas credenciais.

Execute a aplicação via sua IDE (ex: IntelliJ) ou com o comando:
./mvnw spring-boot:run
