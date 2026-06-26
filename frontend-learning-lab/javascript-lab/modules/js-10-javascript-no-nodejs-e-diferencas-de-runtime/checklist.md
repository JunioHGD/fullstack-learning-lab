# Checklist — JS-10: JavaScript no Node.js e diferenças de runtime

Use este checklist para acompanhar o avanço real do módulo. Marque os itens somente quando conseguir explicar e aplicar o conteúdo com segurança básica.

## Progresso por tópico

### 1. JS-10.01 — O que é Node.js como runtime JavaScript

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-10.01.01 — Node.js como runtime
  - [ ] Entendi o objetivo: Entender o papel do Node.js como runtime JavaScript.
  - [ ] Consigo demonstrar o resultado esperado: Explicar por que JavaScript pode rodar fora do navegador.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 2. JS-10.02 — Diferenças centrais entre navegador e Node.js

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-10.02.01 — Navegador versus Node.js
  - [ ] Entendi o objetivo: Comparar linguagem compartilhada e APIs específicas por ambiente.
  - [ ] Consigo demonstrar o resultado esperado: Explicar por que código pode funcionar em um ambiente e falhar no outro.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 3. JS-10.03 — Ausência de window, document e DOM no Node

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-10.03.01 — Sem window, document e DOM no Node
  - [ ] Entendi o objetivo: Reconhecer que window, document e DOM pertencem ao navegador.
  - [ ] Consigo demonstrar o resultado esperado: Evitar confundir linguagem JavaScript com APIs do navegador.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 4. JS-10.04 — Globais e APIs específicas de Node

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-10.04.01 — Globais do Node.js
  - [ ] Entendi o objetivo: Reconhecer globais específicos do Node.js.
  - [ ] Consigo demonstrar o resultado esperado: Identificar APIs que não pertencem ao JavaScript puro.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.
- [ ] JS-10.04.02 — APIs específicas de Node.js
  - [ ] Entendi o objetivo: Entender a existência de APIs próprias do runtime sem aprofundá-las.
  - [ ] Consigo demonstrar o resultado esperado: Distinguir API de runtime de recurso da linguagem.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 5. JS-10.05 — process e variáveis de ambiente em nível introdutório

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-10.05.01 — process
  - [ ] Entendi o objetivo: Usar process para acessar informações básicas do processo Node.js.
  - [ ] Consigo demonstrar o resultado esperado: Reconhecer process como API do Node.js.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.
- [ ] JS-10.05.02 — Variáveis de ambiente
  - [ ] Entendi o objetivo: Ler variáveis de ambiente em nível introdutório.
  - [ ] Consigo demonstrar o resultado esperado: Usar process.env em scripts simples.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 6. JS-10.06 — CommonJS scope-only globals

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-10.06.01 — Globais CommonJS
  - [ ] Entendi o objetivo: Reconhecer __dirname, __filename, exports, module e require.
  - [ ] Consigo demonstrar o resultado esperado: Ler código CommonJS com consciência de escopo próprio.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 7. JS-10.07 — REPL, execução por CLI e organização por arquivos

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-10.07.01 — REPL e CLI
  - [ ] Entendi o objetivo: Usar Node.js no REPL e pela linha de comando.
  - [ ] Consigo demonstrar o resultado esperado: Executar código e scripts pelo terminal.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.
- [ ] JS-10.07.02 — Organização por arquivos
  - [ ] Entendi o objetivo: Organizar scripts Node.js em arquivos separados.
  - [ ] Consigo demonstrar o resultado esperado: Criar scripts simples com estrutura mínima de arquivos.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

### 8. JS-10.08 — Relação entre I/O não bloqueante e event loop no Node

- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi `assimilation-questions.md`.
- [ ] Revisei ou criei exercícios em `exercises/`.

#### Aulas

- [ ] JS-10.08.01 — I/O não bloqueante
  - [ ] Entendi o objetivo: Entender por que Node.js usa operações não bloqueantes.
  - [ ] Consigo demonstrar o resultado esperado: Explicar a relação entre I/O e assincronismo em Node.js.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.
- [ ] JS-10.08.02 — Event loop no Node.js
  - [ ] Entendi o objetivo: Relacionar event loop do Node.js com tarefas assíncronas.
  - [ ] Consigo demonstrar o resultado esperado: Conectar event loop, callbacks, promises e I/O no Node.js.
  - [ ] Registrei dúvidas, observações ou exemplos próprios.

## Fechamento do módulo

- [ ] Revisei todos os tópicos do módulo.
- [ ] Consegui explicar a relação entre os tópicos.
- [ ] Respondi às perguntas de `interview-questions.md`.
- [ ] Identifiquei pontos fracos para revisar depois.
- [ ] Planejei ou desenvolvi o projeto em `docs/projects/js-10-javascript-no-nodejs-e-diferencas-de-runtime/`.
- [ ] Registrei aprendizados principais e dúvidas pendentes.
