# Checklist — JS-08: Assincronismo, event loop e promises

Use este checklist para acompanhar o avanço real do módulo. Marque os itens somente quando conseguir explicar e aplicar o conteúdo com segurança básica.

## Progresso por tópico

### 1. JS-08.01 — Modelo de execução e event loop

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-08.01.01 — Modelo de execução
  - [ ] Entendi o objetivo: Entender execução síncrona e pilha de chamadas em visão conceitual.
  - [ ] Consigo demonstrar o resultado esperado: Explicar a ordem básica de execução do código.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.
- [ ] JS-08.01.02 — Event loop
  - [ ] Entendi o objetivo: Entender o event loop como base da coordenação assíncrona.
  - [ ] Consigo demonstrar o resultado esperado: Prever a ordem de logs síncronos e assíncronos simples.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 2. JS-08.02 — Tarefas assíncronas e callbacks

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-08.02.01 — Tarefas assíncronas
  - [ ] Entendi o objetivo: Distinguir execução imediata de tarefas agendadas.
  - [ ] Consigo demonstrar o resultado esperado: Reconhecer por que operações assíncronas não bloqueiam o fluxo.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.
- [ ] JS-08.02.02 — Callbacks assíncronos
  - [ ] Entendi o objetivo: Usar callbacks em tarefas assíncronas simples.
  - [ ] Consigo demonstrar o resultado esperado: Explicar limitações de callbacks em fluxos complexos.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 3. JS-08.03 — Timers

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-08.03.01 — setTimeout e setInterval
  - [ ] Entendi o objetivo: Usar setTimeout e setInterval para agendamento simples.
  - [ ] Consigo demonstrar o resultado esperado: Prever a ordem de execução envolvendo timers.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 4. JS-08.04 — Promises: criação, estados e encadeamento

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-08.04.01 — Criação e estados de promises
  - [ ] Entendi o objetivo: Criar promises e reconhecer estados pending, fulfilled e rejected.
  - [ ] Consigo demonstrar o resultado esperado: Explicar os estados fundamentais de uma promise.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.
- [ ] JS-08.04.02 — Encadeamento com then
  - [ ] Entendi o objetivo: Encadear operações com then e retorno de valores.
  - [ ] Consigo demonstrar o resultado esperado: Ler e escrever chains simples de promises.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 5. JS-08.05 — Tratamento de erro com promises

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-08.05.01 — catch e finally em promises
  - [ ] Entendi o objetivo: Tratar rejeições com catch e finalizar fluxos com finally.
  - [ ] Consigo demonstrar o resultado esperado: Tratar sucesso e falha em promises sem quebrar o fluxo.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 6. JS-08.06 — async function

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-08.06.01 — async function
  - [ ] Entendi o objetivo: Entender que funções async sempre retornam promises.
  - [ ] Consigo demonstrar o resultado esperado: Criar funções async simples e interpretar seu retorno.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 7. JS-08.07 — await

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-08.07.01 — await
  - [ ] Entendi o objetivo: Usar await para escrever fluxo assíncrono sequencial e legível.
  - [ ] Consigo demonstrar o resultado esperado: Reescrever chains simples usando async/await.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 8. JS-08.08 — try/catch com código assíncrono

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-08.08.01 — try/catch com async/await
  - [ ] Entendi o objetivo: Combinar try/catch com await para capturar falhas assíncronas.
  - [ ] Consigo demonstrar o resultado esperado: Tratar erros em funções async com clareza.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 9. JS-08.09 — Coordenação com Promise.all, Promise.allSettled, Promise.race e Promise.any

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-08.09.01 — Promise.all e Promise.allSettled
  - [ ] Entendi o objetivo: Coordenar múltiplas promises quando todas importam.
  - [ ] Consigo demonstrar o resultado esperado: Escolher entre falhar rápido e coletar todos os resultados.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.
- [ ] JS-08.09.02 — Promise.race e Promise.any
  - [ ] Entendi o objetivo: Coordenar múltiplas promises por primeira resolução ou primeiro sucesso.
  - [ ] Consigo demonstrar o resultado esperado: Reconhecer casos de uso para race e any.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

## Fechamento do módulo

- [ ] Revisei todos os tópicos do módulo.
- [ ] Consegui explicar a relação entre os tópicos.
- [ ] Respondi às perguntas de `interview-questions.md`.
- [ ] Identifiquei pontos fracos para revisar depois.
- [ ] Planejei ou desenvolvi o projeto em `docs/projects/js-08-assincronismo-event-loop-e-promises/`.
- [ ] Registrei aprendizados principais e dúvidas pendentes.
