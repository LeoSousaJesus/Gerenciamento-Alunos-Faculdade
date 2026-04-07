<img src="https://img.shields.io/badge/STATUS-CONCLUÍDO-green"/>

# Gerenciamento de Alunos - CRUD Spring Boot

## Sobre o Projeto:

Uma aplicação web modelada no padrão MVC em Java e construída com o Spring Boot, o projeto conta com uma estrutura de CRUD, no qual os dados estão sendo persistidos em um banco de dados (MySQL). Na camada de visualização foi utilizado HTML, CSS, o framework Bootstrap e o template Thymeleaf. Também foi utilizado o JavaScript e o jQuery para validação de uma regra de negócio. O sistema possui outras funcionalidades como, tela de login/cadastro, criptografia de dados do usuário e validação de campos.

## Tecnologias Utilizadas

- **Linguagem:** Java 17
- **Framework Principal:** Spring Boot 2.6.7
- **Banco de Dados:** MySQL
- **Persistência de Dados:** Spring Data JPA / Hibernate
- **Gerenciador de Dependências:** Maven
- **Desenvolvimento Web:** Spring Web, Spring Boot Starter Validation
- **Camada de Visualização (Frontend):**
  - HTML / CSS
  - Thymeleaf
  - Bootstrap 5.1.3 (via WebJars)
  - JavaScript / jQuery 3.6.0 (via WebJars)
- **Ferramentas de Desenvolvimento:** Spring Boot DevTools
- **Testes:** Spring Boot Starter Test

## Demonstração

![demo](https://user-images.githubusercontent.com/89096854/170026187-57aa04f4-189b-4c00-8cc8-16a1227a5eb7.gif)

### Formulário de Cadastro
![formulario de cadastro](https://user-images.githubusercontent.com/89096854/170031976-645e9bd8-eaca-4a84-805c-588100e1a770.PNG)

### Lista de Alunos
![Lista de alunos](https://user-images.githubusercontent.com/89096854/170031981-68cf5454-a727-467c-82e6-1ba2f53c2900.PNG)


## Estrutura do Banco de Dados

### Entidade Aluno
![Entidade Aluno](https://user-images.githubusercontent.com/89096854/170030916-5c05c8c3-71d7-432e-aa6c-02b0ccf30409.PNG)

### Entidade Usuário
![Entidade Usuario](https://user-images.githubusercontent.com/89096854/170030921-8948e471-b0c1-4fcc-94aa-4bc94a554df9.PNG)

## Instalação

O projeto é gerenciado pelo Maven. Para utilizá-lo, basta clonar o repositório e importá-lo em sua IDE (como IntelliJ IDEA, Eclipse ou VS Code).

## Configurações do Banco de Dados

Para rodar a aplicação localmente, você deve criar um banco de dados MySQL com o nome de sua preferência. Depois, é necessário adequar o projeto de acordo com as suas credenciais. Abra o arquivo `application.properties`, localizado em `gerenciamento-alunos-crud-springboot-master-main/src/main/resources/application.properties` e altere os seguintes parâmetros:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/nome-do-seu-banco-de-dados?useTimezone=true&serverTimezone=UTC
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
```

## Execução

Após configurar o banco de dados e as dependências (Maven), execute o projeto através de sua IDE rodando a classe principal do Spring Boot.
Abra um navegador de sua preferência e acesse: `http://localhost:8080`
