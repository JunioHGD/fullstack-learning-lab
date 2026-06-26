# Checklist — BACKEND-05 — Validação, Serialização, Erros e Logs

## Objetivo do módulo

Consolidar qualidade de entrada e saída da API, tratamento consistente de erros e logs básicos.

## Como usar este checklist

Marque cada item conforme avançar. O checklist representa os conteúdos do módulo de forma organizada por tópico e por aula.

## 1. 05.01 — Validação e normalização de entrada

**Objetivo do tópico:** Garantir que dados recebidos pela API sejam válidos e previsíveis.

### Aulas

- [ ] **05.01.01 — Validação de entrada no servidor**
  - [ ] Li e compreendi a seção correspondente em `topics/05-01-input-validation-normalization/lessons.md`.
  - [ ] Entendi o objetivo: Entender por que toda entrada deve ser validada no backend.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar por que validação frontend não substitui validação backend.
  - [ ] Respondi às perguntas de assimilação em `topics/05-01-input-validation-normalization/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/05-01-input-validation-normalization/exercises/` quando necessário.

- [ ] **05.01.02 — Normalização de dados recebidos**
  - [ ] Li e compreendi a seção correspondente em `topics/05-01-input-validation-normalization/lessons.md`.
  - [ ] Entendi o objetivo: Preparar dados recebidos para uso consistente na aplicação.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer casos simples de normalização de dados.
  - [ ] Respondi às perguntas de assimilação em `topics/05-01-input-validation-normalization/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/05-01-input-validation-normalization/exercises/` quando necessário.
## 2. 05.02 — JSON, serialização e desserialização

**Objetivo do tópico:** Compreender troca e transformação de dados entre API e cliente.

### Aulas

- [ ] **05.02.01 — JSON como formato de troca**
  - [ ] Li e compreendi a seção correspondente em `topics/05-02-json-serialization/lessons.md`.
  - [ ] Entendi o objetivo: Entender JSON como formato comum de comunicação em APIs.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar o papel do JSON em requests e responses.
  - [ ] Respondi às perguntas de assimilação em `topics/05-02-json-serialization/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/05-02-json-serialization/exercises/` quando necessário.

- [ ] **05.02.02 — Serialização e desserialização**
  - [ ] Li e compreendi a seção correspondente em `topics/05-02-json-serialization/lessons.md`.
  - [ ] Entendi o objetivo: Entender conversão entre objetos da aplicação e dados trafegados.
  - [ ] Verifiquei se atingi o resultado esperado: Diferenciar serialização e desserialização.
  - [ ] Respondi às perguntas de assimilação em `topics/05-02-json-serialization/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/05-02-json-serialization/exercises/` quando necessário.
## 3. 05.03 — Schemas de request e response

**Objetivo do tópico:** Definir contratos previsíveis para entrada e saída da API.

### Aulas

- [ ] **05.03.01 — Schemas de request**
  - [ ] Li e compreendi a seção correspondente em `topics/05-03-request-response-schemas/lessons.md`.
  - [ ] Entendi o objetivo: Representar o formato esperado de dados recebidos.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar como schema de request reduz ambiguidade.
  - [ ] Respondi às perguntas de assimilação em `topics/05-03-request-response-schemas/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/05-03-request-response-schemas/exercises/` quando necessário.

- [ ] **05.03.02 — Schemas de response**
  - [ ] Li e compreendi a seção correspondente em `topics/05-03-request-response-schemas/lessons.md`.
  - [ ] Entendi o objetivo: Representar o formato esperado de dados retornados.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar como schema de response melhora consistência.
  - [ ] Respondi às perguntas de assimilação em `topics/05-03-request-response-schemas/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/05-03-request-response-schemas/exercises/` quando necessário.
## 4. 05.04 — Tratamento centralizado de erros

**Objetivo do tópico:** Padronizar falhas e respostas de erro da API.

### Aulas

- [ ] **05.04.01 — Tratamento centralizado de erros**
  - [ ] Li e compreendi a seção correspondente em `topics/05-04-error-handling/lessons.md`.
  - [ ] Entendi o objetivo: Entender por que erros devem seguir fluxo centralizado.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar o papel de um handler global de erro.
  - [ ] Respondi às perguntas de assimilação em `topics/05-04-error-handling/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/05-04-error-handling/exercises/` quando necessário.

- [ ] **05.04.02 — Mapeamento de erros para status codes e resposta consistente**
  - [ ] Li e compreendi a seção correspondente em `topics/05-04-error-handling/lessons.md`.
  - [ ] Entendi o objetivo: Relacionar tipos de erro a status codes e formatos de resposta.
  - [ ] Verifiquei se atingi o resultado esperado: Escolher status e formato adequados para erros comuns.
  - [ ] Respondi às perguntas de assimilação em `topics/05-04-error-handling/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/05-04-error-handling/exercises/` quando necessário.
## 5. 05.05 — Logs estruturados e correlação

**Objetivo do tópico:** Introduzir logs úteis para manutenção e depuração.

### Aulas

- [ ] **05.05.01 — Logs estruturados**
  - [ ] Li e compreendi a seção correspondente em `topics/05-05-structured-logs-correlation/lessons.md`.
  - [ ] Entendi o objetivo: Entender logs estruturados como base para análise de comportamento.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer informações úteis em logs de backend.
  - [ ] Respondi às perguntas de assimilação em `topics/05-05-structured-logs-correlation/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/05-05-structured-logs-correlation/exercises/` quando necessário.

- [ ] **05.05.02 — Correlação entre request, erro e log**
  - [ ] Li e compreendi a seção correspondente em `topics/05-05-structured-logs-correlation/lessons.md`.
  - [ ] Entendi o objetivo: Relacionar requisições, falhas e registros para investigação.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar como logs ajudam a rastrear erros.
  - [ ] Respondi às perguntas de assimilação em `topics/05-05-structured-logs-correlation/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/05-05-structured-logs-correlation/exercises/` quando necessário.

---

## Fechamento do módulo

- [ ] Revisei todos os tópicos do módulo.
- [ ] Reforcei os conceitos que ainda estavam frágeis.
- [ ] Respondi ou revisei as perguntas de `interview-questions.md`.
- [ ] Organizei exemplos e exercícios relevantes.
- [ ] Desenvolvi ou planejei o projeto de conclusão em `docs/projects/backend-05-validation-serialization-errors-logs/`.
- [ ] Escrevi observações finais sobre o que aprendi.
