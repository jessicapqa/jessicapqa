# 🌐 Web Automation

**Code Journey | Web Test Automation**

## 📌 Sobre o projeto

Este projeto faz parte do **Code Journey** e tem como objetivo desenvolver estruturas de automação de testes para aplicações Web, explorando diferentes frameworks e linguagens de programação.

A proposta é implementar e comparar diferentes abordagens de automação, aplicando boas práticas de desenvolvimento, organização de código, reutilização de componentes e manutenção de scripts.

## 🎯 Objetivos

- Desenvolver frameworks de automação Web.
- Explorar diferentes ferramentas e linguagens.
- Automatizar fluxos funcionais de aplicações de e-commerce.
- Implementar testes positivos e negativos.
- Aplicar padrões de projeto, como Page Object Model (POM).
- Explorar geração de evidências e relatórios de execução.

## 🛠️ Tecnologias e ferramentas

| Framework | Linguagem |
|---|---|
| Playwright | Python |
| Selenium | Python |
| Cypress | TypeScript |
| Robot Framework | Python |

## 🛒 Aplicações de teste

Os projetos utilizarão aplicações públicas destinadas à prática de automação:

- [SauceDemo](https://www.saucedemo.com/) – Aplicação de e-commerce.
- [DemoQA](https://demoqa.com/) – Aplicação para testes de elementos, formulários e componentes Web.

## 🧪 Cenários de testes

### SauceDemo — E-commerce

- Login e autenticação.
- Validação de credenciais.
- Listagem e visualização de produtos.
- Ordenação de produtos.
- Adição e remoção de produtos do carrinho.
- Validação do carrinho de compras.
- Preenchimento de dados do cliente.
- Finalização de compra (Checkout).
- Validação de mensagens de sucesso e erro.

### DemoQA

- Text Box.
- Check Box.
- Radio Button.
- Web Tables.
- Buttons.
- Links.
- Upload e Download.
- Dynamic Properties.
- Forms.

## 📂 Estrutura sugerida

```text
web/
│
├── playwright-python/
│   ├── tests/
│   ├── pages/
│   ├── data/
│   ├── utils/
│   ├── conftest.py
│   ├── requirements.txt
│   └── README.md
│
├── selenium-python/
│   ├── tests/
│   ├── pages/
│   ├── drivers/
│   ├── utils/
│   ├── requirements.txt
│   └── README.md
│
├── cypress-typescript/
│   ├── cypress/
│   │   ├── e2e/
│   │   ├── fixtures/
│   │   └── support/
│   ├── cypress.config.ts
│   ├── package.json
│   └── README.md
│
└── robot-framework/
    ├── tests/
    ├── resources/
    ├── libraries/
    ├── data/
    ├── results/
    └── README.md
```

## ▶️ Execução dos projetos

Cada framework terá suas próprias configurações e dependências.

**Playwright com Python**
```bash
pip install -r requirements.txt
playwright install
pytest
```

**Selenium com Python**
```bash
pip install -r requirements.txt
pytest
```

**Cypress com TypeScript**
```bash
npm install
npx cypress open
```

Para execução em modo headless:
```bash
npx cypress run
```

**Robot Framework**
```bash
pip install robotframework
robot -d results tests/
```

## 📊 Resultados e evidências

Os projetos poderão gerar:
- Relatórios de execução.
- Logs.
- Evidências de testes.
- Screenshots em caso de falhas.

---

**Code Journey | Web Automation**

*Learn. Build. Test. Evolve.*