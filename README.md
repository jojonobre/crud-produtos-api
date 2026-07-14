<div align="center">

# CRUD Produtos API (under construction)

### API REST para gerenciamento de produtos desenvolvida com Java e Spring Boot.

Este projeto tem como objetivo praticar conceitos de desenvolvimento backend, APIs REST, documentação de endpoints e testes, além de servir como base para futuras implementações relacionadas à Qualidade de Software e Automação de Testes.

</div>

---

## Tecnologias Utilizadas

<div align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,maven,docker" />
</div>

### Ferramentas e Bibliotecas

- Java 21
- Spring Boot
- Maven
- Swagger / OpenAPI
- JUnit 5
- Docker

---

## Funcionalidades

### Produtos

- Criar produto
- Listar produtos
- Buscar produto por ID
- Atualizar produto
- Excluir produto

### API REST

- Endpoints RESTful
- Respostas em JSON
- Estrutura organizada em camadas
- Documentação automática com Swagger

---

## Endpoints

| Método | Endpoint | Descrição |
|----------|----------|----------|
| POST | `/produtos` | Criar produto |
| GET | `/produtos` | Listar produtos |
| GET | `/produtos/{id}` | Buscar produto por ID |
| PUT | `/produtos/{id}` | Atualizar produto |
| DELETE | `/produtos/{id}` | Excluir produto |

---

## Documentação da API

Após iniciar a aplicação, a documentação poderá ser acessada através do Swagger UI:

```text
http://localhost:8080/swagger-ui/index.html
```

---

## Executando o Projeto

### Clonar repositório

```bash
git clone https://github.com/jojonobre/crud-produtos-api
```

### Executar aplicação

```bash
mvn spring-boot:run
```

### Executar testes

```bash
mvn test
```

---

## Docker

Build da imagem:

```bash
docker build -t crud-produtos-api .
```

Executar container:

```bash
docker run -p 8080:8080 crud-produtos-api
```

---

## Estrutura do Projeto

```text
src
├── main
│   ├── controller
│   ├── service
│   ├── model
│   └── exception
│
└── test
```

---

## Roadmap

Próximas funcionalidades planejadas para evolução do projeto:

- [ ] Banco de dados H2
- [ ] Persistência com Spring Data JPA
- [ ] Validações de dados
- [ ] Tratamento global de exceções
- [ ] Testes de API com Postman
- [ ] Automação de testes de API com Playwright
- [ ] Docker Compose
- [ ] Pipeline CI/CD com GitHub Actions
- [ ] Cobertura de testes

---

## Objetivo do Projeto

Este projeto faz parte dos meus estudos em:

- Desenvolvimento Backend com Java
- APIs REST com Spring Boot
- Documentação de APIs
- Qualidade de Software
- Testes Automatizados
- Boas práticas de desenvolvimento

---

<div align="center">

### Joyce Maria 💜

Estudante de Ciência da Computação • QA Analyst Intern

<a href="https://github.com/jojonobre">
  <img src="https://img.shields.io/badge/GitHub-Perfil-181717?style=for-the-badge&logo=github">
</a>

</div>
