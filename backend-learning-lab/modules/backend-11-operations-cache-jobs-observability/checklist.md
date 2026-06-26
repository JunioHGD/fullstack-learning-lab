# Checklist — BACKEND-11 — Operação Backend, Cache, Jobs e Observabilidade

## Objetivo do módulo

Introduzir padrões operacionais: paginação, filtros, cache, upload, filas, jobs, logs, métricas, traces e escala inicial.

## Como usar este checklist

Marque cada item conforme avançar. O checklist representa os conteúdos do módulo de forma organizada por tópico e por aula.

## 1. 11.01 — Paginação, filtros e ordenação

**Objetivo do tópico:** Controlar retorno de coleções em APIs.

### Aulas

- [ ] **11.01.01 — Paginação em coleções**
  - [ ] Li e compreendi a seção correspondente em `topics/11-01-pagination-filtering-ordering/lessons.md`.
  - [ ] Entendi o objetivo: Entender por que coleções precisam ser paginadas.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar riscos de retornar listas ilimitadas.
  - [ ] Respondi às perguntas de assimilação em `topics/11-01-pagination-filtering-ordering/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-01-pagination-filtering-ordering/exercises/` quando necessário.

- [ ] **11.01.02 — Filtros e ordenação**
  - [ ] Li e compreendi a seção correspondente em `topics/11-01-pagination-filtering-ordering/lessons.md`.
  - [ ] Entendi o objetivo: Aplicar seleção e ordenação de resultados em APIs.
  - [ ] Verifiquei se atingi o resultado esperado: Projetar parâmetros básicos de filtro e ordenação.
  - [ ] Respondi às perguntas de assimilação em `topics/11-01-pagination-filtering-ordering/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-01-pagination-filtering-ordering/exercises/` quando necessário.
## 2. 11.02 — Cache HTTP e cache de aplicação

**Objetivo do tópico:** Reduzir custo e latência com cache em nível introdutório.

### Aulas

- [ ] **11.02.01 — Cache HTTP**
  - [ ] Li e compreendi a seção correspondente em `topics/11-02-http-application-cache/lessons.md`.
  - [ ] Entendi o objetivo: Entender cache baseado em semântica HTTP.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer quando respostas HTTP podem ser cacheadas.
  - [ ] Respondi às perguntas de assimilação em `topics/11-02-http-application-cache/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-02-http-application-cache/exercises/` quando necessário.

- [ ] **11.02.02 — Cache de aplicação**
  - [ ] Li e compreendi a seção correspondente em `topics/11-02-http-application-cache/lessons.md`.
  - [ ] Entendi o objetivo: Introduzir cache controlado pela aplicação.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar benefícios e riscos de cache na aplicação.
  - [ ] Respondi às perguntas de assimilação em `topics/11-02-http-application-cache/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-02-http-application-cache/exercises/` quando necessário.
## 3. 11.03 — Redis como apoio a cache e sessão

**Objetivo do tópico:** Conhecer Redis como serviço auxiliar de backend.

### Aulas

- [ ] **11.03.01 — Redis para cache**
  - [ ] Li e compreendi a seção correspondente em `topics/11-03-redis-cache-session/lessons.md`.
  - [ ] Entendi o objetivo: Entender uso de Redis para cache temporário.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar um caso comum de uso de Redis.
  - [ ] Respondi às perguntas de assimilação em `topics/11-03-redis-cache-session/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-03-redis-cache-session/exercises/` quando necessário.

- [ ] **11.03.02 — Redis para sessão e expiração**
  - [ ] Li e compreendi a seção correspondente em `topics/11-03-redis-cache-session/lessons.md`.
  - [ ] Entendi o objetivo: Relacionar Redis com sessões e dados expirados.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer Redis como apoio a sessões e TTL.
  - [ ] Respondi às perguntas de assimilação em `topics/11-03-redis-cache-session/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-03-redis-cache-session/exercises/` quando necessário.
## 4. 11.04 — Upload de arquivos e multipart/form-data

**Objetivo do tópico:** Receber arquivos em APIs de forma controlada.

### Aulas

- [ ] **11.04.01 — multipart/form-data**
  - [ ] Li e compreendi a seção correspondente em `topics/11-04-file-upload-multipart/lessons.md`.
  - [ ] Entendi o objetivo: Diferenciar envio de arquivos de JSON comum.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar o papel de multipart/form-data.
  - [ ] Respondi às perguntas de assimilação em `topics/11-04-file-upload-multipart/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-04-file-upload-multipart/exercises/` quando necessário.

- [ ] **11.04.02 — Upload, validação e armazenamento inicial**
  - [ ] Li e compreendi a seção correspondente em `topics/11-04-file-upload-multipart/lessons.md`.
  - [ ] Entendi o objetivo: Introduzir cuidados básicos com upload.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer validações essenciais em upload.
  - [ ] Respondi às perguntas de assimilação em `topics/11-04-file-upload-multipart/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-04-file-upload-multipart/exercises/` quando necessário.
## 5. 11.05 — Filas, publishers, consumers e jobs

**Objetivo do tópico:** Executar tarefas fora do fluxo síncrono da requisição.

### Aulas

- [ ] **11.05.01 — Filas, publishers e consumers**
  - [ ] Li e compreendi a seção correspondente em `topics/11-05-queues-background-jobs/lessons.md`.
  - [ ] Entendi o objetivo: Entender componentes básicos de mensageria.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar publisher, fila e consumer em alto nível.
  - [ ] Respondi às perguntas de assimilação em `topics/11-05-queues-background-jobs/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-05-queues-background-jobs/exercises/` quando necessário.

- [ ] **11.05.02 — Jobs em background**
  - [ ] Li e compreendi a seção correspondente em `topics/11-05-queues-background-jobs/lessons.md`.
  - [ ] Entendi o objetivo: Identificar tarefas adequadas para processamento assíncrono.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer quando usar job em background.
  - [ ] Respondi às perguntas de assimilação em `topics/11-05-queues-background-jobs/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-05-queues-background-jobs/exercises/` quando necessário.
## 6. 11.06 — Observabilidade

**Objetivo do tópico:** Observar comportamento da aplicação em execução.

### Aulas

- [ ] **11.06.01 — Logs, métricas e traces**
  - [ ] Li e compreendi a seção correspondente em `topics/11-06-observability/lessons.md`.
  - [ ] Entendi o objetivo: Diferenciar sinais de observabilidade.
  - [ ] Verifiquei se atingi o resultado esperado: Explicar diferenças entre logs, métricas e traces.
  - [ ] Respondi às perguntas de assimilação em `topics/11-06-observability/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-06-observability/exercises/` quando necessário.

- [ ] **11.06.02 — Monitoramento e alertas introdutórios**
  - [ ] Li e compreendi a seção correspondente em `topics/11-06-observability/lessons.md`.
  - [ ] Entendi o objetivo: Introduzir acompanhamento e alerta de saúde da aplicação.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer o papel de monitoramento e alertas.
  - [ ] Respondi às perguntas de assimilação em `topics/11-06-observability/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-06-observability/exercises/` quando necessário.
## 7. 11.07 — Gargalos, throughput e escalabilidade inicial

**Objetivo do tópico:** Introduzir noções básicas de desempenho e escala.

### Aulas

- [ ] **11.07.01 — Gargalos, throughput e latência**
  - [ ] Li e compreendi a seção correspondente em `topics/11-07-performance-scalability-basics/lessons.md`.
  - [ ] Entendi o objetivo: Entender métricas e fatores básicos de desempenho.
  - [ ] Verifiquei se atingi o resultado esperado: Diferenciar gargalo, throughput e latência.
  - [ ] Respondi às perguntas de assimilação em `topics/11-07-performance-scalability-basics/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-07-performance-scalability-basics/exercises/` quando necessário.

- [ ] **11.07.02 — Noções iniciais de escalabilidade**
  - [ ] Li e compreendi a seção correspondente em `topics/11-07-performance-scalability-basics/lessons.md`.
  - [ ] Entendi o objetivo: Introduzir limites e crescimento de aplicações backend.
  - [ ] Verifiquei se atingi o resultado esperado: Reconhecer fatores que afetam escalabilidade.
  - [ ] Respondi às perguntas de assimilação em `topics/11-07-performance-scalability-basics/assimilation-questions.md`.
  - [ ] Registrei dúvidas, exemplos ou observações.
  - [ ] Criei ou atualizei exercícios em `topics/11-07-performance-scalability-basics/exercises/` quando necessário.

---

## Fechamento do módulo

- [ ] Revisei todos os tópicos do módulo.
- [ ] Reforcei os conceitos que ainda estavam frágeis.
- [ ] Respondi ou revisei as perguntas de `interview-questions.md`.
- [ ] Organizei exemplos e exercícios relevantes.
- [ ] Desenvolvi ou planejei o projeto de conclusão em `docs/projects/backend-11-operations-cache-jobs-observability/`.
- [ ] Escrevi observações finais sobre o que aprendi.
