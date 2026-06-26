# Checklist — BACKEND-07 — PostgreSQL, Repositórios, ORM e Migrations

## Objetivo do módulo

Aplicar persistência real com PostgreSQL, transações, repositories, ORM e migrations.

## Como usar este checklist

Marque cada item conforme avançar. O checklist representa os conteúdos do módulo de forma organizada por tópico e por aula.

## 1. 07.01 — PostgreSQL como banco principal

**Objetivo do tópico:** Conhecer PostgreSQL como banco relacional principal do Lab.

### Aulas

- [ ] **07.01.01 — PostgreSQL no Backend Learning Lab**
  - [ ] Li e compreendi a seção correspondente em `topics/07-01-postgresql-basics/lessons.md`.
  - [ ] Entendi o objetivo: Entender o papel do PostgreSQL na trilha backend.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar por que PostgreSQL é usado como banco principal.
  - [ ] Respondi às perguntas de assimilação em `topics/07-01-postgresql-basics/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/07-01-postgresql-basics/exercises/` quando necessário.

- [ ] **07.01.02 — Tipos, schemas, tabelas e constraints no PostgreSQL**
  - [ ] Li e compreendi a seção correspondente em `topics/07-01-postgresql-basics/lessons.md`.
  - [ ] Entendi o objetivo: Conhecer estruturas e tipos relevantes no PostgreSQL.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer elementos básicos de schema no PostgreSQL.
  - [ ] Respondi às perguntas de assimilação em `topics/07-01-postgresql-basics/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/07-01-postgresql-basics/exercises/` quando necessário.
## 2. 07.02 — Transações e isolamento

**Objetivo do tópico:** Entender consistência em operações com múltiplas queries.

### Aulas

- [ ] **07.02.01 — Transações**
  - [ ] Li e compreendi a seção correspondente em `topics/07-02-transactions-isolation/lessons.md`.
  - [ ] Entendi o objetivo: Compreender commit e rollback.
  - [ ] Verifiquei se atingi o resultado esperado: Identificar quando usar transação.
  - [ ] Respondi às perguntas de assimilação em `topics/07-02-transactions-isolation/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/07-02-transactions-isolation/exercises/` quando necessário.

- [ ] **07.02.02 — Isolamento de transações**
  - [ ] Li e compreendi a seção correspondente em `topics/07-02-transactions-isolation/lessons.md`.
  - [ ] Entendi o objetivo: Introduzir conflitos e isolamento entre transações.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar por que isolamento importa em concorrência.
  - [ ] Respondi às perguntas de assimilação em `topics/07-02-transactions-isolation/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/07-02-transactions-isolation/exercises/` quando necessário.
## 3. 07.03 — SQL direto e repositories

**Objetivo do tópico:** Conectar aplicação a dados preservando separação de responsabilidades.

### Aulas

- [ ] **07.03.01 — SQL direto para acesso a dados**
  - [ ] Li e compreendi a seção correspondente em `topics/07-03-direct-sql-repositories/lessons.md`.
  - [ ] Entendi o objetivo: Entender acesso a dados por queries explícitas.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer vantagens de aprender SQL antes de ORM.
  - [ ] Respondi às perguntas de assimilação em `topics/07-03-direct-sql-repositories/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/07-03-direct-sql-repositories/exercises/` quando necessário.

- [ ] **07.03.02 — Repositories como fronteira de persistência**
  - [ ] Li e compreendi a seção correspondente em `topics/07-03-direct-sql-repositories/lessons.md`.
  - [ ] Entendi o objetivo: Aplicar repositories para isolar persistência.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar a fronteira entre service e repository.
  - [ ] Respondi às perguntas de assimilação em `topics/07-03-direct-sql-repositories/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/07-03-direct-sql-repositories/exercises/` quando necessário.
## 4. 07.04 — ORMs, trade-offs e Prisma

**Objetivo do tópico:** Introduzir ORMs sem substituir fundamentos SQL.

### Aulas

- [ ] **07.04.01 — ORMs e trade-offs**
  - [ ] Li e compreendi a seção correspondente em `topics/07-04-orm-prisma/lessons.md`.
  - [ ] Entendi o objetivo: Comparar benefícios e custos de usar ORM.
  - [ ] Verifiquei se atingi o resultado esperado: Analisar quando ORM ajuda ou atrapalha.
  - [ ] Respondi às perguntas de assimilação em `topics/07-04-orm-prisma/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/07-04-orm-prisma/exercises/` quando necessário.

- [ ] **07.04.02 — Prisma ORM em nível introdutório-profissional**
  - [ ] Li e compreendi a seção correspondente em `topics/07-04-orm-prisma/lessons.md`.
  - [ ] Entendi o objetivo: Conhecer Prisma como opção moderna de ORM.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer conceitos básicos do Prisma.
  - [ ] Respondi às perguntas de assimilação em `topics/07-04-orm-prisma/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/07-04-orm-prisma/exercises/` quando necessário.
## 5. 07.05 — Migrations e evolução de schema

**Objetivo do tópico:** Versionar mudanças estruturais no banco.

### Aulas

- [ ] **07.05.01 — Migrations e histórico de migrations**
  - [ ] Li e compreendi a seção correspondente em `topics/07-05-migrations-schema-evolution/lessons.md`.
  - [ ] Entendi o objetivo: Entender migrations como histórico de evolução do schema.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar por que schema precisa ser versionado.
  - [ ] Respondi às perguntas de assimilação em `topics/07-05-migrations-schema-evolution/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/07-05-migrations-schema-evolution/exercises/` quando necessário.

- [ ] **07.05.02 — Migrations em desenvolvimento e produção**
  - [ ] Li e compreendi a seção correspondente em `topics/07-05-migrations-schema-evolution/lessons.md`.
  - [ ] Entendi o objetivo: Diferenciar aplicação de migrations localmente e em produção.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer cuidados de migrations em ambientes reais.
  - [ ] Respondi às perguntas de assimilação em `topics/07-05-migrations-schema-evolution/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/07-05-migrations-schema-evolution/exercises/` quando necessário.

---

## Fechamento do módulo

- [ ] Revisei todos os tópicos do módulo.
- [ ] Reforcei os conceitos que ainda estavam frágeis.
- [ ] Respondi ou revisei as perguntas de `interview-questions.md`.
- [ ] Organizei exemplos e exercícios relevantes.
- [ ] Desenvolvi ou planejei o projeto de conclusão em `docs/projects/backend-07-postgresql-repositories-orm-migrations/`.
- [ ] Escrevi observações finais sobre o que aprendi.
