# 🔌 API Automation

**Code Journey | API Test Automation**

## 📌 Sobre o projeto

Este projeto faz parte do **Code Journey** e tem como objetivo desenvolver estruturas de automação de testes para APIs e serviços, explorando diferentes frameworks e linguagens de programação.

A proposta é construir soluções para validação de endpoints, contratos, respostas, integrações e regras de negócio, aplicando boas práticas de automação e organização dos testes.

## 🎯 Objetivos

- Desenvolver frameworks de automação para APIs REST.
- Explorar diferentes linguagens e ferramentas.
- Automatizar requisições e validações HTTP.
- Implementar cenários positivos e negativos.
- Validar contratos e estruturas de respostas.
- Trabalhar com autenticação e autorização.
- Explorar testes de integração e regressão.
- Desenvolver estruturas reutilizáveis e de fácil manutenção.

## 🛠️ Tecnologias e ferramentas

| Framework | Linguagem |
|---|---|
| Robot Framework | Python |
| Playwright | TypeScript |
| Cypress | JavaScript |
| REST Assured | Java |

**Ferramentas de apoio:**
- Postman.
- Git.
- Maven.
- Node.js.
- Python.
- Java JDK.

## 🧪 Cenários de testes

### Requisições HTTP

- GET – Consulta de informações.
- POST – Criação de registros.
- PUT – Atualização completa.
- PATCH – Atualização parcial.
- DELETE – Exclusão de registros.

### Validações

- Status codes HTTP.
- Headers.
- Payloads e estruturas JSON.
- Tipos de dados.
- Campos obrigatórios.
- Regras de negócio.
- Mensagens de erro.
- Autenticação e autorização.
- Contratos de API.

### Cenários positivos e negativos

- Requisições com dados válidos.
- Requisições com dados inválidos.
- Campos obrigatórios ausentes.
- Dados em formatos incorretos.
- Recursos inexistentes.
- Acessos não autorizados.
- Validação de respostas inesperadas.

## 📂 Estrutura sugerida

```text
api/
│
├── robot-framework/
│   ├── tests/
│   ├── resources/
│   ├── libraries/
│   ├── variables/
│   ├── data/
│   ├── results/
│   └── README.md
│
├── playwright-typescript/
│   ├── tests/
│   ├── fixtures/
│   ├── utils/
│   ├── playwright.config.ts
│   ├── package.json
│   └── README.md
│
├── cypress-javascript/
│   ├── cypress/
│   │   ├── e2e/
│   │   ├── fixtures/
│   │   └── support/
│   ├── cypress.config.js
│   ├── package.json
│   └── README.md
│
└── rest-assured-java/
    ├── src/
    │   └── test/
    ├── pom.xml
    └── README.md
```

## ⚙️ Configuração do ambiente

**Pré-requisitos:**
- Python.
- Java JDK.
- Maven.
- Node.js.
- NPM.
- Robot Framework.
- Postman (apoio para exploração e validação manual das APIs).

## ▶️ Execução dos projetos

**Robot Framework**
```bash
pip install robotframework
pip install robotframework-requests

robot -d results tests/
```

**Playwright com TypeScript**
```bash
npm install
npx playwright test
```

**Cypress com JavaScript**
```bash
npm install
npx cypress run
```

**REST Assured com Java**
```bash
mvn clean test
```

## 📊 Resultados e evidências

Os projetos poderão gerar:
- Relatórios de execução.
- Logs de requisições e respostas.
- Evidências de falhas.
- Validações de contratos.
- Resultados de testes automatizados.

---

**Code Journey | API Automation**

*Learn. Build. Test. Evolve.*