# ℹ️ Ajuda Rápida

Este arquivo contém instruções rápidas para rodar e testar o projeto.

---

## 🔧 Requisitos
- Java 17+ instalado (`java -version`)
- Maven instalado (`mvn -v`)

---

## ▶️ Executando a aplicação
1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPO>
   cd TDD-test-driven-development-main
   ```
2. Rode a aplicação:
   ```bash
   mvn spring-boot:run
   ```
3. Acesse no navegador:  
   [http://localhost:8080](http://localhost:8080)

---

## 🧪 Rodando os testes
```bash
mvn test
```
Os testes estão localizados em `src/test/java/com/example/projetotdd`.

- `ProdutoTest.java` → validações da entidade Produto  
- `ComissaoTest.java` → cálculo de comissão  
- `ProdutoControllerTest.java` → endpoints REST  

---

## ❓ Dúvidas frequentes
- **Posso usar outro banco além do H2?**  
  Sim. Basta alterar o `application.properties` para apontar para outro banco (MySQL, PostgreSQL, etc.).

- **O que acontece se eu não rodar os testes?**  
  A aplicação sobe normalmente, mas perde a segurança de regressão garantida pelo TDD.

---

## 🛠️ Manutenção
Sempre que adicionar uma nova funcionalidade:
1. Escreva o **teste primeiro**.  
2. Implemente a lógica até o teste passar.  
3. Refatore se necessário.  

Assim, o projeto segue fiel ao ciclo **TDD**.
