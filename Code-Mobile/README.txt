# 📱 Mobile Automation

**Code Journey | Mobile Test Automation**

## 📌 Sobre o projeto

Este projeto faz parte do **Code Journey** e tem como objetivo desenvolver estruturas de automação de testes para aplicações Mobile, explorando diferentes tecnologias, frameworks e linguagens de programação.

A proposta é trabalhar com automação de aplicações Android e iOS, explorando interações com elementos nativos, navegação entre telas, validações funcionais e execução em dispositivos físicos e emuladores.

## 🎯 Objetivos

- Desenvolver estruturas de automação Mobile.
- Explorar o Appium com diferentes linguagens.
- Implementar automações utilizando Robot Framework e Java.
- Trabalhar com JUnit para organização e execução de testes.
- Aplicar padrões de projeto e boas práticas.
- Explorar execução automatizada e integração contínua com Jenkins.

## 🛠️ Tecnologias e ferramentas

| Framework / Ferramenta | Linguagem |
|---|---|
| Robot Framework + Appium | Python |
| Appium | Java |
| JUnit | Java |

**Ferramentas de apoio:**
- Appium Server.
- Android Studio.
- Android Emulator.
- Xcode / iOS Simulator (quando aplicável).
- Jenkins.
- Git.

## 🧪 Cenários de testes

Os cenários serão desenvolvidos conforme as funcionalidades das aplicações utilizadas para os testes.

**Principais fluxos:**
- Inicialização e encerramento da aplicação.
- Login e autenticação.
- Navegação entre telas.
- Interação com elementos nativos.
- Preenchimento de formulários.
- Validação de mensagens e componentes.
- Gestos de swipe, scroll e long press.
- Tratamento de teclado e alertas.
- Testes funcionais e de regressão.

## 📂 Estrutura sugerida

```text
mobile/
│
├── robot-appium/
│   ├── tests/
│   ├── resources/
│   ├── libraries/
│   ├── variables/
│   ├── results/
│   └── README.md
│
├── java-appium/
│   ├── src/
│   │   ├── main/
│   │   └── test/
│   ├── pom.xml
│   └── README.md
│
└── junit/
    ├── src/
    │   └── test/
    ├── pom.xml
    └── README.md
```

## ⚙️ Configuração do ambiente

Para execução dos testes, serão utilizadas ferramentas e dependências específicas de cada implementação.

**Pré-requisitos:**
- Python.
- Java JDK.
- Maven.
- Node.js.
- Appium Server.
- Android Studio.
- Emulador Android ou dispositivo físico.

## ▶️ Execução dos projetos

**Robot Framework + Appium**
```bash
pip install robotframework
pip install robotframework-appiumlibrary

robot -d results tests/
```

**Java + Appium / JUnit**

Com Maven:
```bash
mvn clean test
```

A configuração do Appium Server, dispositivo e capabilities deverá estar definida antes da execução.

## 🔄 CI/CD — Jenkins

O Jenkins será utilizado para explorar processos de integração e execução contínua dos testes Mobile.

**Objetivos da integração:**
- Automatizar a execução dos testes.
- Configurar pipelines de execução.
- Integrar o repositório ao Jenkins.
- Gerar relatórios de execução.
- Armazenar evidências dos testes.
- Acompanhar resultados das execuções.

## 📊 Resultados e evidências

- Relatórios de execução.
- Logs de automação.
- Screenshots.
- Evidências de falhas.
- Resultados de testes JUnit.

---

**Code Journey | Mobile Automation**

*Learn. Build. Test. Evolve.*