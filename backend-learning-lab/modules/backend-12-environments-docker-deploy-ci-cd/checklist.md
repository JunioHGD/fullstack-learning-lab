# Checklist — BACKEND-12 — Ambientes, Docker, Deploy e CI/CD

## Objetivo do módulo

Fechar a trilha com ambientes, configuração, build, Docker, Compose, deploy, CI/CD, migrations e segredos no pipeline.

## Como usar este checklist

Marque cada item conforme avançar. O checklist representa os conteúdos do módulo de forma organizada por tópico e por aula.

## 1. 12.01 — Ambientes e configuração

**Objetivo do tópico:** Separar desenvolvimento, homologação e produção.

### Aulas

- [ ] **12.01.01 — Desenvolvimento, homologação e produção**
  - [ ] Li e compreendi a seção correspondente em `topics/12-01-environments-configuration/lessons.md`.
  - [ ] Entendi o objetivo: Entender diferenças entre ambientes.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar por que ambientes devem ser separados.
  - [ ] Respondi às perguntas de assimilação em `topics/12-01-environments-configuration/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-01-environments-configuration/exercises/` quando necessário.

- [ ] **12.01.02 — Configuração por ambiente**
  - [ ] Li e compreendi a seção correspondente em `topics/12-01-environments-configuration/lessons.md`.
  - [ ] Entendi o objetivo: Relacionar variáveis e configurações a cada ambiente.
  - [ ] Verifiquei se atingi o resultado esperado: Definir configurações específicas por ambiente.
  - [ ] Respondi às perguntas de assimilação em `topics/12-01-environments-configuration/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-01-environments-configuration/exercises/` quando necessário.
## 2. 12.02 — Build e empacotamento

**Objetivo do tópico:** Preparar aplicação para execução fora do desenvolvimento local.

### Aulas

- [ ] **12.02.01 — Build da aplicação**
  - [ ] Li e compreendi a seção correspondente em `topics/12-02-build-packaging/lessons.md`.
  - [ ] Entendi o objetivo: Entender processo de build em backend TypeScript.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar diferença entre código fonte e artefato executável.
  - [ ] Respondi às perguntas de assimilação em `topics/12-02-build-packaging/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-02-build-packaging/exercises/` quando necessário.

- [ ] **12.02.02 — Empacotamento e scripts de produção**
  - [ ] Li e compreendi a seção correspondente em `topics/12-02-build-packaging/lessons.md`.
  - [ ] Entendi o objetivo: Organizar scripts e artefatos para produção.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer scripts comuns de produção.
  - [ ] Respondi às perguntas de assimilação em `topics/12-02-build-packaging/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-02-build-packaging/exercises/` quando necessário.
## 3. 12.03 — Docker, imagens e containers

**Objetivo do tópico:** Padronizar execução com containers.

### Aulas

- [ ] **12.03.01 — Docker, imagens e containers**
  - [ ] Li e compreendi a seção correspondente em `topics/12-03-docker-images-containers/lessons.md`.
  - [ ] Entendi o objetivo: Entender conceitos fundamentais de Docker.
  - [ ] Verifiquei se atingi o resultado esperado: Diferenciar imagem e container.
  - [ ] Respondi às perguntas de assimilação em `topics/12-03-docker-images-containers/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-03-docker-images-containers/exercises/` quando necessário.

- [ ] **12.03.02 — Dockerfile**
  - [ ] Li e compreendi a seção correspondente em `topics/12-03-docker-images-containers/lessons.md`.
  - [ ] Entendi o objetivo: Compreender Dockerfile como receita de imagem.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar etapas básicas de criação de imagem.
  - [ ] Respondi às perguntas de assimilação em `topics/12-03-docker-images-containers/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-03-docker-images-containers/exercises/` quando necessário.
## 4. 12.04 — Docker Compose e serviços locais

**Objetivo do tópico:** Rodar aplicação, banco e serviços auxiliares em ambiente local reproduzível.

### Aulas

- [ ] **12.04.01 — Docker Compose**
  - [ ] Li e compreendi a seção correspondente em `topics/12-04-docker-compose-local-services/lessons.md`.
  - [ ] Entendi o objetivo: Entender Compose como orquestração local simples.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar o papel do compose.yaml.
  - [ ] Respondi às perguntas de assimilação em `topics/12-04-docker-compose-local-services/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-04-docker-compose-local-services/exercises/` quando necessário.

- [ ] **12.04.02 — Aplicação, banco e serviços auxiliares locais**
  - [ ] Li e compreendi a seção correspondente em `topics/12-04-docker-compose-local-services/lessons.md`.
  - [ ] Entendi o objetivo: Compor API, PostgreSQL e serviços como Redis em desenvolvimento.
  - [ ] Verifiquei se atingi o resultado esperado: Descrever uma stack local com múltiplos serviços.
  - [ ] Respondi às perguntas de assimilação em `topics/12-04-docker-compose-local-services/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-04-docker-compose-local-services/exercises/` quando necessário.
## 5. 12.05 — Conceitos básicos de deploy

**Objetivo do tópico:** Entender publicação controlada de aplicações backend.

### Aulas

- [ ] **12.05.01 — Conceitos básicos de deploy**
  - [ ] Li e compreendi a seção correspondente em `topics/12-05-deploy-basics/lessons.md`.
  - [ ] Entendi o objetivo: Compreender o caminho geral de publicação de uma API.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar etapas básicas de deploy.
  - [ ] Respondi às perguntas de assimilação em `topics/12-05-deploy-basics/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-05-deploy-basics/exercises/` quando necessário.

- [ ] **12.05.02 — Release e configuração de produção**
  - [ ] Li e compreendi a seção correspondente em `topics/12-05-deploy-basics/lessons.md`.
  - [ ] Entendi o objetivo: Relacionar release com configuração segura de produção.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer cuidados antes de publicar.
  - [ ] Respondi às perguntas de assimilação em `topics/12-05-deploy-basics/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-05-deploy-basics/exercises/` quando necessário.
## 6. 12.06 — CI/CD com GitHub Actions

**Objetivo do tópico:** Automatizar validação, testes e entrega.

### Aulas

- [ ] **12.06.01 — Workflows, jobs e runners**
  - [ ] Li e compreendi a seção correspondente em `topics/12-06-github-actions-ci-cd/lessons.md`.
  - [ ] Entendi o objetivo: Entender componentes básicos do GitHub Actions.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar workflow, job e runner.
  - [ ] Respondi às perguntas de assimilação em `topics/12-06-github-actions-ci-cd/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-06-github-actions-ci-cd/exercises/` quando necessário.

- [ ] **12.06.02 — Testes automáticos e deploy automatizado básico**
  - [ ] Li e compreendi a seção correspondente em `topics/12-06-github-actions-ci-cd/lessons.md`.
  - [ ] Entendi o objetivo: Relacionar CI/CD com testes e deploy.
  - [ ] Verifiquei se atingi o resultado esperado: Descrever pipeline básico de validação e entrega.
  - [ ] Respondi às perguntas de assimilação em `topics/12-06-github-actions-ci-cd/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-06-github-actions-ci-cd/exercises/` quando necessário.
## 7. 12.07 — Migrations, segredos e release seguro

**Objetivo do tópico:** Tratar riscos finais de entrega em pipeline.

### Aulas

- [ ] **12.07.01 — Migrations em pipeline**
  - [ ] Li e compreendi a seção correspondente em `topics/12-07-pipeline-migrations-secrets-release/lessons.md`.
  - [ ] Entendi o objetivo: Entender cuidados ao aplicar migrations durante entrega.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer riscos de migrations automatizadas.
  - [ ] Respondi às perguntas de assimilação em `topics/12-07-pipeline-migrations-secrets-release/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-07-pipeline-migrations-secrets-release/exercises/` quando necessário.

- [ ] **12.07.02 — Segredos no pipeline e release seguro**
  - [ ] Li e compreendi a seção correspondente em `topics/12-07-pipeline-migrations-secrets-release/lessons.md`.
  - [ ] Entendi o objetivo: Proteger variáveis sensíveis e validar release.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar cuidados com segredos em CI/CD.
  - [ ] Respondi às perguntas de assimilação em `topics/12-07-pipeline-migrations-secrets-release/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/12-07-pipeline-migrations-secrets-release/exercises/` quando necessário.

---

## Fechamento do módulo

- [ ] Revisei todos os tópicos do módulo.
- [ ] Reforcei os conceitos que ainda estavam frágeis.
- [ ] Respondi ou revisei as perguntas de `interview-questions.md`.
- [ ] Organizei exemplos e exercícios relevantes.
- [ ] Desenvolvi ou planejei o projeto de conclusão em `docs/projects/backend-12-environments-docker-deploy-ci-cd/`.
- [ ] Escrevi observações finais sobre o que aprendi.
