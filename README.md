# 💻 Bruno Bianchini

### Engenheiro de Qualidade de Software Sênior · Automação E2E, API & Performance · IA aplicada a QA

🇧🇷 Trabalho com qualidade de software desde 2019. Hoje cuido de qualidade em **fluxos críticos de
receita** — cobrança e billing — onde falha não vira reclamação, vira prejuízo. Passei um ano e oito
meses como **Engenheiro de Produto**, respondendo por roadmap e backlog, e voltei para qualidade
sabendo ler risco de negócio — isso mudou os cenários que eu escrevo. Trabalho com automação E2E e de
API, testes de performance, e agentes próprios de IA aplicados à escrita e manutenção de testes.

🇬🇧 Software Quality Engineer since 2019. Today I own quality in **revenue-critical flows** — billing
and charging — where a failure isn't a complaint, it's a loss. I spent a year and a half as a
**Product Engineer** owning roadmap and backlog, and came back to QA able to read business risk, which
changed the scenarios I write. I work with E2E and API automation, performance testing, and custom AI
agents applied to writing and maintaining tests.

---

## 🧪 QA Stack

![Cypress](https://img.shields.io/badge/Cypress-69D3A7?style=flat-square&logo=cypress&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![AI-assisted QA](https://img.shields.io/badge/IA%20aplicada%20a%20QA-000000?style=flat-square&logo=anthropic&logoColor=white)

Cypress · Playwright · Postman · Bruno · k6 · JMeter · TypeScript · JavaScript · Node.js · SQL ·
CI/CD · BDD (Gherkin/Cucumber) · LLMs aplicados a QA

---

## 💡 Projetos em Destaque

### [qe-kit](https://github.com/bianchinibruno/qe-kit) — skills de engenharia de qualidade para Claude Code

Plugin instalável com skills de escopo estreito e contrato definido: revisão de PR com seis lentes
independentes em paralelo, testes de integração que provam alguma coisa, cobertura de critérios de
aceite, diagnóstico de performance com k6 e autoria de testes de API.

**Resultados — demonstrados e reproduzíveis** contra o `sandbox-cobranca` do próprio repositório (uma
API com bugs plantados):

- A revisão multiagente **pegou os três bugs plantados**, cada um pela lente certa — idempotência
  (débito em dobro), arredondamento de centavos e autorização (IDOR) — e a lente de contrato ficou
  corretamente silenciosa, provando que as lentes são disjuntas.
- **Prova de regressão:** asserções vacuosas (`toBeDefined`, `every()` sobre array vazio) reescritas
  passam a **falhar quando o código está errado** e a passar com o fix — `99≠100`, `200≠100`,
  `200≠403`. Um teste que não falha com o bug não prova nada.

> A diferença que o repositório faz questão de mostrar: resultado que você **roda**, não que você
> acredita.

---

## 📊 Experiência & Resultados

Resultados de projetos ao longo da carreira em QA:

- **70% de redução** no tempo da suíte regressiva E2E, refatorando a arquitetura de testes e
  automatizando os cenários críticos (Cypress, Playwright).
- **Até 65% de queda** no tempo de resposta de APIs, a partir de testes de carga com k6 e JMeter e do
  diagnóstico dos gargalos.
- **80% de economia de tempo** na escrita e manutenção de testes E2E, API e Integração com agentes
  próprios de IA generativa (Claude, Cursor).

---

## 🤝 Vamos conversar

Aberto a conversas sobre QA Sênior, Staff QA e Tech Lead de Qualidade.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bianchinibruno)
