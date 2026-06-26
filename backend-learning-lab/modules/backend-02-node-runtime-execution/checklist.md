# Checklist — BACKEND-02 — Node.js e Modelo de Execução Backend

## Objetivo do módulo

Introduzir Node.js como runtime backend e explicar módulos, event loop, I/O assíncrono e servidor HTTP sem framework.

## Como usar este checklist

Marque cada item conforme avançar. O checklist representa os conteúdos do módulo de forma organizada por tópico e por aula.

## 1. 02.01 — Node.js como runtime backend

**Objetivo do tópico:** Entender Node.js como ambiente de execução JavaScript fora do navegador.

### Aulas

- [ ] **02.01.01 — O que é Node.js**
  - [ ] Li e compreendi a seção correspondente em `topics/02-01-node-runtime/lessons.md`.
  - [ ] Entendi o objetivo: Compreender Node.js como runtime usado no backend.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar o papel do Node.js em aplicações backend.
  - [ ] Respondi às perguntas de assimilação em `topics/02-01-node-runtime/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/02-01-node-runtime/exercises/` quando necessário.

- [ ] **02.01.02 — Node.js, navegador, processo e ambiente**
  - [ ] Li e compreendi a seção correspondente em `topics/02-01-node-runtime/lessons.md`.
  - [ ] Entendi o objetivo: Diferenciar execução no Node.js e no navegador.
  - [ ] Verifiquei se atingi o resultado esperado: Identificar diferenças entre runtime backend e ambiente do navegador.
  - [ ] Respondi às perguntas de assimilação em `topics/02-01-node-runtime/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/02-01-node-runtime/exercises/` quando necessário.
## 2. 02.02 — Módulos nativos relevantes

**Objetivo do tópico:** Conhecer módulos nativos usados como base de aplicações backend.

### Aulas

- [ ] **02.02.01 — Módulos nativos do Node.js**
  - [ ] Li e compreendi a seção correspondente em `topics/02-02-native-modules/lessons.md`.
  - [ ] Entendi o objetivo: Reconhecer módulos nativos relevantes para backend.
  - [ ] Verifiquei se atingi o resultado esperado: Identificar módulos úteis para HTTP, arquivos e caminhos.
  - [ ] Respondi às perguntas de assimilação em `topics/02-02-native-modules/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/02-02-native-modules/exercises/` quando necessário.

- [ ] **02.02.02 — Introdução ao módulo node:http**
  - [ ] Li e compreendi a seção correspondente em `topics/02-02-native-modules/lessons.md`.
  - [ ] Entendi o objetivo: Entender o módulo HTTP nativo como base de servidores em Node.js.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer como Node.js lida com mensagens HTTP em baixo nível.
  - [ ] Respondi às perguntas de assimilação em `topics/02-02-native-modules/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/02-02-native-modules/exercises/` quando necessário.
## 3. 02.03 — Event loop e I/O não bloqueante

**Objetivo do tópico:** Compreender o modelo assíncrono que sustenta servidores Node.js.

### Aulas

- [ ] **02.03.01 — Event loop e I/O não bloqueante**
  - [ ] Li e compreendi a seção correspondente em `topics/02-03-event-loop-nonblocking-io/lessons.md`.
  - [ ] Entendi o objetivo: Entender como Node.js lida com operações assíncronas e I/O.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar por que I/O não bloqueante é importante em backends.
  - [ ] Respondi às perguntas de assimilação em `topics/02-03-event-loop-nonblocking-io/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/02-03-event-loop-nonblocking-io/exercises/` quando necessário.

- [ ] **02.03.02 — Eventos, concorrência e limites do single-thread**
  - [ ] Li e compreendi a seção correspondente em `topics/02-03-event-loop-nonblocking-io/lessons.md`.
  - [ ] Entendi o objetivo: Introduzir arquitetura orientada a eventos, concorrência e limites do modelo single-thread.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer benefícios e limites do modelo de execução do Node.js.
  - [ ] Respondi às perguntas de assimilação em `topics/02-03-event-loop-nonblocking-io/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/02-03-event-loop-nonblocking-io/exercises/` quando necessário.
## 4. 02.04 — Servidor HTTP sem framework

**Objetivo do tópico:** Criar a base conceitual de servidores HTTP antes de usar frameworks.

### Aulas

- [ ] **02.04.01 — Servidor HTTP com node:http**
  - [ ] Li e compreendi a seção correspondente em `topics/02-04-http-server-without-framework/lessons.md`.
  - [ ] Entendi o objetivo: Entender a criação de servidor HTTP usando apenas módulo nativo.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar request, response e resposta JSON em servidor mínimo.
  - [ ] Respondi às perguntas de assimilação em `topics/02-04-http-server-without-framework/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/02-04-http-server-without-framework/exercises/` quando necessário.

- [ ] **02.04.02 — Limites do servidor sem framework**
  - [ ] Li e compreendi a seção correspondente em `topics/02-04-http-server-without-framework/lessons.md`.
  - [ ] Entendi o objetivo: Reconhecer problemas que frameworks resolvem.
  - [ ] Verifiquei se atingi o resultado esperado: Justificar o uso posterior de Express ou Fastify.
  - [ ] Respondi às perguntas de assimilação em `topics/02-04-http-server-without-framework/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/02-04-http-server-without-framework/exercises/` quando necessário.

---

## Fechamento do módulo

- [ ] Revisei todos os tópicos do módulo.
- [ ] Reforcei os conceitos que ainda estavam frágeis.
- [ ] Respondi ou revisei as perguntas de `interview-questions.md`.
- [ ] Organizei exemplos e exercícios relevantes.
- [ ] Desenvolvi ou planejei o projeto de conclusão em `docs/projects/backend-02-node-runtime-execution/`.
- [ ] Escrevi observações finais sobre o que aprendi.
