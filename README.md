# 🧪 Projeto TDD com Spring Boot

Este repositório demonstra o uso de **Test-Driven Development (TDD)** em uma aplicação Java com **Spring Boot** e **Maven**.  
A aplicação implementa operações básicas de produtos e cálculo de comissão, acompanhadas por testes unitários e de integração.

---

## 🚀 Tecnologias
- Java 17+
- Spring Boot 2.x
- Spring Web
- Spring Data JPA
- H2 Database (memória, para testes)
- JUnit 5

---

## 📂 Estrutura
```
src/
 ├── main/
 │   ├── java/com/example/projetotdd
 │   │    ├── controller/ → ProdutoController.java
 │   │    ├── model/ → Produto.java, Comissao.java
 │   │    ├── service/ → ProdutoService.java
 │   │    └── ProjetoTddApplication.java
 │   └── resources/ → application.properties
 └── test/
     ├── java/com/example/projetotdd
     │    ├── ProdutoTest.java
     │    ├── ComissaoTest.java
     │    ├── ProdutoControllerTest.java
     │    └── ProjetoTddApplicationTests.java
     └── resources/
```

---

## ▶️ Como executar

### Rodar a aplicação
```bash
mvn spring-boot:run
```

A aplicação sobe na porta **8080** por padrão.

### Rodar os testes
```bash
mvn test
```

---

## 🧪 Filosofia TDD
O desenvolvimento foi feito seguindo as etapas:
1. **Red** – escrever o teste primeiro (falhando).
2. **Green** – implementar o mínimo necessário para passar no teste.
3. **Refactor** – refatorar mantendo a cobertura dos testes.

---
