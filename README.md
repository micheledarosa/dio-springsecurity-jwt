# Projeto Spring Security com JWT e H2 Database 🔐

Este é um projeto Spring Boot que demonstra a implementação de autenticação e autorização utilizando Spring Security, JSON Web Tokens (JWT) e o banco de dados H2.

O projeto foi realizado durante o curso *Adicionando Segurança a uma API REST com Spring Security* da [DIO](https://www.dio.me/).

## Estrutura do Projeto 🗃️

- 📁 **.mvn/wrapper**: Contém os arquivos necessários para o Maven Wrapper, que permite a execução do Maven sem a necessidade de uma instalação global.
- 📁 **src/main/java/dio/spring/security/jwt**: O código-fonte Java do projeto.
    - **controller**: Controladores responsáveis por lidar com as requisições HTTP.
    - **dtos**: Data Transfer Objects (DTOs) para mapeamento de dados entre a camada de controle e a camada de serviço.
    - **model**: Modelos de dados da aplicação.
    - **repository**: Interfaces de repositório para acesso a dados.
    - **security**: Configurações de segurança, incluindo a configuração do Spring Security.
    - **service**: Implementações de serviços para lógica de negócios.
- 📁 **src/main/resources**: Recursos da aplicação, como arquivos de propriedades de configuração e scripts SQL para inicialização do banco de dados H2.
- 📁 **src/test/java/dio/spring/security/jwt**: Testes unitários e de integração.
- 📄 **.gitignore**: Arquivo especificando os padrões de arquivos e diretórios a serem ignorados pelo controle de versão do Git.
- 📄 **mvnw** e **mvnw.cmd**: Scripts do Maven Wrapper para facilitar a construção e execução do projeto.
- 📄 **pom.xml**: Arquivo de configuração do Maven que define as dependências e plugins do projeto.

## Banco de Dados H2 🎲

O projeto utiliza o banco de dados H2, um banco de dados em memória, para armazenar dados de forma temporária durante o desenvolvimento e teste da aplicação. O H2 é configurado no arquivo `application.properties`.

## Executando o Projeto ⚡

Para construir e executar o projeto localmente, você pode utilizar o Maven Wrapper incluído no projeto:

```bash
./mvnw spring-boot:run
