# Checklist — BACKEND-09 — Segurança de Backend e APIs

## Objetivo do módulo

Introduzir segurança de APIs como competência transversal: HTTPS, OWASP, validação, cookies, headers, CORS, segredos e logging seguro.

## Como usar este checklist

Marque cada item conforme avançar. O checklist representa os conteúdos do módulo de forma organizada por tópico e por aula.

## 1. 09.01 — HTTPS e segurança por padrão

**Objetivo do tópico:** Entender proteção de tráfego e decisões seguras desde o início.

### Aulas

- [ ] **09.01.01 — HTTPS e proteção do tráfego**
  - [ ] Li e compreendi a seção correspondente em `topics/09-01-https-secure-defaults/lessons.md`.
  - [ ] Entendi o objetivo: Compreender a necessidade de proteger dados em trânsito.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar por que APIs em produção devem usar HTTPS.
  - [ ] Respondi às perguntas de assimilação em `topics/09-01-https-secure-defaults/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/09-01-https-secure-defaults/exercises/` quando necessário.

- [ ] **09.01.02 — Segurança por padrão no backend**
  - [ ] Li e compreendi a seção correspondente em `topics/09-01-https-secure-defaults/lessons.md`.
  - [ ] Entendi o objetivo: Introduzir mentalidade de segurança por padrão.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer decisões simples que reduzem risco.
  - [ ] Respondi às perguntas de assimilação em `topics/09-01-https-secure-defaults/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/09-01-https-secure-defaults/exercises/` quando necessário.
## 2. 09.02 — OWASP para aplicações web e APIs

**Objetivo do tópico:** Conhecer riscos clássicos e específicos de APIs.

### Aulas

- [ ] **09.02.01 — OWASP Top 10 para aplicações web**
  - [ ] Li e compreendi a seção correspondente em `topics/09-02-owasp-web-api-risks/lessons.md`.
  - [ ] Entendi o objetivo: Conhecer categorias principais de riscos web.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer riscos comuns em aplicações web.
  - [ ] Respondi às perguntas de assimilação em `topics/09-02-owasp-web-api-risks/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/09-02-owasp-web-api-risks/exercises/` quando necessário.

- [ ] **09.02.02 — OWASP API Security Top 10**
  - [ ] Li e compreendi a seção correspondente em `topics/09-02-owasp-web-api-risks/lessons.md`.
  - [ ] Entendi o objetivo: Conhecer riscos comuns específicos de APIs.
  - [ ] Verifiquei se atingi o resultado esperado: Relacionar falhas de API a riscos OWASP.
  - [ ] Respondi às perguntas de assimilação em `topics/09-02-owasp-web-api-risks/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/09-02-owasp-web-api-risks/exercises/` quando necessário.
## 3. 09.03 — Validação, erros e exposição de dados

**Objetivo do tópico:** Usar validação e respostas controladas como defesa.

### Aulas

- [ ] **09.03.01 — Validação no servidor como controle de segurança**
  - [ ] Li e compreendi a seção correspondente em `topics/09-03-validation-error-data-exposure/lessons.md`.
  - [ ] Entendi o objetivo: Reforçar validação como controle de segurança.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar como validação reduz superfície de ataque.
  - [ ] Respondi às perguntas de assimilação em `topics/09-03-validation-error-data-exposure/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/09-03-validation-error-data-exposure/exercises/` quando necessário.

- [ ] **09.03.02 — Exposição mínima de erros e dados**
  - [ ] Li e compreendi a seção correspondente em `topics/09-03-validation-error-data-exposure/lessons.md`.
  - [ ] Entendi o objetivo: Evitar vazamento de detalhes internos em respostas.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer erros e respostas que expõem dados demais.
  - [ ] Respondi às perguntas de assimilação em `topics/09-03-validation-error-data-exposure/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/09-03-validation-error-data-exposure/exercises/` quando necessário.
## 4. 09.04 — Cookies seguros, security headers e CORS

**Objetivo do tópico:** Configurar mecanismos HTTP com foco em segurança.

### Aulas

- [ ] **09.04.01 — Cookies seguros**
  - [ ] Li e compreendi a seção correspondente em `topics/09-04-secure-cookies-headers-cors/lessons.md`.
  - [ ] Entendi o objetivo: Entender atributos de cookies importantes para segurança.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer flags como HttpOnly, Secure e SameSite.
  - [ ] Respondi às perguntas de assimilação em `topics/09-04-secure-cookies-headers-cors/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/09-04-secure-cookies-headers-cors/exercises/` quando necessário.

- [ ] **09.04.02 — Security headers e CORS com credenciais**
  - [ ] Li e compreendi a seção correspondente em `topics/09-04-secure-cookies-headers-cors/lessons.md`.
  - [ ] Entendi o objetivo: Relacionar headers de segurança e riscos de CORS com credenciais.
  - [ ] Verifiquei se atingi o resultado esperado: Identificar configurações inseguras de CORS e headers.
  - [ ] Respondi às perguntas de assimilação em `topics/09-04-secure-cookies-headers-cors/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/09-04-secure-cookies-headers-cors/exercises/` quando necessário.
## 5. 09.05 — Segredos, logging de segurança e superfície de ataque

**Objetivo do tópico:** Proteger credenciais e observar eventos sensíveis sem vazar dados.

### Aulas

- [ ] **09.05.01 — Segredos e credenciais de aplicação**
  - [ ] Li e compreendi a seção correspondente em `topics/09-05-secrets-security-logging-attack-surface/lessons.md`.
  - [ ] Entendi o objetivo: Entender cuidados com segredos, tokens e credenciais.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar por que segredos não devem ir para código, logs ou repositório.
  - [ ] Respondi às perguntas de assimilação em `topics/09-05-secrets-security-logging-attack-surface/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/09-05-secrets-security-logging-attack-surface/exercises/` quando necessário.

- [ ] **09.05.02 — Logging de segurança e revisão de superfícies de ataque**
  - [ ] Li e compreendi a seção correspondente em `topics/09-05-secrets-security-logging-attack-surface/lessons.md`.
  - [ ] Entendi o objetivo: Introduzir registros de segurança e revisão de pontos expostos.
  - [ ] Verifiquei se atingi o resultado esperado: Mapear superfícies de ataque comuns em uma API.
  - [ ] Respondi às perguntas de assimilação em `topics/09-05-secrets-security-logging-attack-surface/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/09-05-secrets-security-logging-attack-surface/exercises/` quando necessário.

---

## Fechamento do módulo

- [ ] Revisei todos os tópicos do módulo.
- [ ] Reforcei os conceitos que ainda estavam frágeis.
- [ ] Respondi ou revisei as perguntas de `interview-questions.md`.
- [ ] Organizei exemplos e exercícios relevantes.
- [ ] Desenvolvi ou planejei o projeto de conclusão em `docs/projects/backend-09-backend-api-security/`.
- [ ] Escrevi observações finais sobre o que aprendi.
