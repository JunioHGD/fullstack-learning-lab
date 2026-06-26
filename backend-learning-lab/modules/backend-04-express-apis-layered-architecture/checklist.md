# Checklist — BACKEND-04 — APIs com Express e Organização em Camadas

## Objetivo do módulo

Construir APIs HTTP com framework e organizar o fluxo em rotas, middlewares, controllers, services e repositories.

## Como usar este checklist

Marque cada item conforme avançar. O checklist representa os conteúdos do módulo de forma organizada por tópico e por aula.

## 1. 04.01 — Frameworks HTTP e bootstrap da aplicação

**Objetivo do tópico:** Entender o papel de frameworks HTTP no backend Node.js.

### Aulas

- [ ] **04.01.01 — Papel de um framework HTTP**
  - [ ] Li e compreendi a seção correspondente em `topics/04-01-http-frameworks-bootstrap/lessons.md`.
  - [ ] Entendi o objetivo: Compreender o que frameworks abstraem em relação ao node:http.
  - [ ] Verifiquei se atingi o resultado esperado: Justificar o uso de framework para APIs.
  - [ ] Respondi às perguntas de assimilação em `topics/04-01-http-frameworks-bootstrap/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/04-01-http-frameworks-bootstrap/exercises/` quando necessário.

- [ ] **04.01.02 — Express, Fastify e bootstrap**
  - [ ] Li e compreendi a seção correspondente em `topics/04-01-http-frameworks-bootstrap/lessons.md`.
  - [ ] Entendi o objetivo: Conhecer Express como base e Fastify como comparação moderna.
  - [ ] Verifiquei se atingi o resultado esperado: Identificar a estrutura mínima de inicialização de uma API.
  - [ ] Respondi às perguntas de assimilação em `topics/04-01-http-frameworks-bootstrap/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/04-01-http-frameworks-bootstrap/exercises/` quando necessário.
## 2. 04.02 — Rotas e entrada de dados

**Objetivo do tópico:** Definir endpoints e receber dados por params, query e body.

### Aulas

- [ ] **04.02.01 — Definição de rotas**
  - [ ] Li e compreendi a seção correspondente em `topics/04-02-routes-request-inputs/lessons.md`.
  - [ ] Entendi o objetivo: Criar rotas HTTP em framework backend.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer rotas como pontos de entrada da API.
  - [ ] Respondi às perguntas de assimilação em `topics/04-02-routes-request-inputs/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/04-02-routes-request-inputs/exercises/` quando necessário.

- [ ] **04.02.02 — Parâmetros de rota, query string e body**
  - [ ] Li e compreendi a seção correspondente em `topics/04-02-routes-request-inputs/lessons.md`.
  - [ ] Entendi o objetivo: Diferenciar formas de entrada de dados em uma requisição.
  - [ ] Verifiquei se atingi o resultado esperado: Escolher params, query ou body conforme o caso.
  - [ ] Respondi às perguntas de assimilação em `topics/04-02-routes-request-inputs/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/04-02-routes-request-inputs/exercises/` quando necessário.
## 3. 04.03 — Middlewares

**Objetivo do tópico:** Compreender interceptação e composição do fluxo de requisição.

### Aulas

- [ ] **04.03.01 — Middlewares de aplicação**
  - [ ] Li e compreendi a seção correspondente em `topics/04-03-middlewares/lessons.md`.
  - [ ] Entendi o objetivo: Entender middlewares aplicados globalmente.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar como middlewares participam do fluxo da API.
  - [ ] Respondi às perguntas de assimilação em `topics/04-03-middlewares/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/04-03-middlewares/exercises/` quando necessário.

- [ ] **04.03.02 — Middlewares por rota e ordem de execução**
  - [ ] Li e compreendi a seção correspondente em `topics/04-03-middlewares/lessons.md`.
  - [ ] Entendi o objetivo: Entender middlewares específicos e impacto da ordem de registro.
  - [ ] Verifiquei se atingi o resultado esperado: Prever o fluxo de execução de middlewares.
  - [ ] Respondi às perguntas de assimilação em `topics/04-03-middlewares/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/04-03-middlewares/exercises/` quando necessário.
## 4. 04.04 — Controllers e services

**Objetivo do tópico:** Separar entrada HTTP de regra de negócio.

### Aulas

- [ ] **04.04.01 — Controllers**
  - [ ] Li e compreendi a seção correspondente em `topics/04-04-controllers-services/lessons.md`.
  - [ ] Entendi o objetivo: Delimitar a responsabilidade do controller em uma API.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar por que controller deve lidar com entrada e resposta.
  - [ ] Respondi às perguntas de assimilação em `topics/04-04-controllers-services/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/04-04-controllers-services/exercises/` quando necessário.

- [ ] **04.04.02 — Services e fluxo controller-service**
  - [ ] Li e compreendi a seção correspondente em `topics/04-04-controllers-services/lessons.md`.
  - [ ] Entendi o objetivo: Delimitar a responsabilidade do service na regra de negócio.
  - [ ] Verifiquei se atingi o resultado esperado: Diferenciar lógica HTTP de lógica de negócio.
  - [ ] Respondi às perguntas de assimilação em `topics/04-04-controllers-services/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/04-04-controllers-services/exercises/` quando necessário.
## 5. 04.05 — Repositories e modularização

**Objetivo do tópico:** Introduzir fronteira de persistência e organização por domínio ou recurso.

### Aulas

- [ ] **04.05.01 — Repositories como fronteira de persistência**
  - [ ] Li e compreendi a seção correspondente em `topics/04-05-repositories-modularization/lessons.md`.
  - [ ] Entendi o objetivo: Entender o repository como abstração de acesso a dados.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar onde queries ou operações de persistência devem ficar.
  - [ ] Respondi às perguntas de assimilação em `topics/04-05-repositories-modularization/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/04-05-repositories-modularization/exercises/` quando necessário.

- [ ] **04.05.02 — Fluxo controller-service-repository e modularização**
  - [ ] Li e compreendi a seção correspondente em `topics/04-05-repositories-modularization/lessons.md`.
  - [ ] Entendi o objetivo: Organizar a aplicação em camadas e módulos por domínio ou recurso.
  - [ ] Verifiquei se atingi o resultado esperado: Descrever o fluxo completo de uma requisição em camadas.
  - [ ] Respondi às perguntas de assimilação em `topics/04-05-repositories-modularization/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/04-05-repositories-modularization/exercises/` quando necessário.

---

## Fechamento do módulo

- [ ] Revisei todos os tópicos do módulo.
- [ ] Reforcei os conceitos que ainda estavam frágeis.
- [ ] Respondi ou revisei as perguntas de `interview-questions.md`.
- [ ] Organizei exemplos e exercícios relevantes.
- [ ] Desenvolvi ou planejei o projeto de conclusão em `docs/projects/backend-04-express-apis-layered-architecture/`.
- [ ] Escrevi observações finais sobre o que aprendi.
