# Checklist — DOM-05: Eventos, propagação e arquitetura de interação
## Objetivo do módulo

Transformar a árvore DOM em uma interface interativa orientada por eventos do usuário e do navegador.
## Progresso por tópico
### DOM-05.01 — Modelo de eventos e EventTarget
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-05.01.01 — O que são eventos e quem pode recebê-los
  - [ ] Compreendi: Reconhecer eventos do usuário e do navegador e relacioná-los com EventTarget.
  - [ ] Consigo demonstrar: Explicar que elementos, documento e janela podem ser alvos de eventos.

### DOM-05.02 — Registro de ouvintes
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-05.02.01 — addEventListener
  - [ ] Compreendi: Conectar comportamento JavaScript a ocorrências da interface.
  - [ ] Consigo demonstrar: Registrar listeners sem misturar comportamento diretamente na marcação HTML.

### DOM-05.03 — Objeto Event e alvos
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-05.03.01 — Event, target e currentTarget
  - [ ] Compreendi: Diferenciar o elemento que originou o evento do elemento que possui o listener.
  - [ ] Consigo demonstrar: Interpretar corretamente event.target e event.currentTarget em elementos aninhados.

### DOM-05.04 — Propagação de eventos
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-05.04.01 — Captura, alvo e bolha
  - [ ] Compreendi: Compreender as fases de propagação e a ordem de execução de listeners.
  - [ ] Consigo demonstrar: Prever o caminho de um evento em estruturas aninhadas.

### DOM-05.05 — Cancelamento e controle de eventos
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-05.05.01 — preventDefault, stopPropagation e cancelamento
  - [ ] Compreendi: Usar APIs de cancelamento para controlar comportamento padrão e fluxo de propagação.
  - [ ] Consigo demonstrar: Decidir quando impedir comportamento padrão ou interromper propagação sem criar efeitos colaterais.

### DOM-05.06 — Delegação de eventos
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-05.06.01 — Delegação com ancestral comum
  - [ ] Compreendi: Registrar um listener em um ancestral e identificar ações pelo alvo do evento.
  - [ ] Consigo demonstrar: Explicar por que delegação é útil em listas e interfaces atualizadas dinamicamente.

### DOM-05.07 — Eventos customizados
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-05.07.01 — CustomEvent e dispatchEvent
  - [ ] Compreendi: Disparar eventos por código e transportar dados simples por detail.
  - [ ] Consigo demonstrar: Entender eventos como mecanismo de comunicação além das ações diretas do usuário.

### DOM-05.08 — Opções de listener
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-05.08.01 — capture, once, passive e signal
  - [ ] Compreendi: Conhecer opções comuns de addEventListener e seus impactos.
  - [ ] Consigo demonstrar: Usar opções de listener de forma consciente conforme a necessidade de interação.

## Fechamento do módulo

- [ ] Revisei todos os tópicos do módulo.
- [ ] Revisei as principais dúvidas registradas.
- [ ] Respondi às perguntas de entrevista em `interview-questions.md`.
- [ ] Criei ou planejei o projeto em `docs/projects/dom-05-eventos-propagacao-e-arquitetura-de-interacao/`.
- [ ] Documentei aprendizados importantes antes de avançar para o próximo módulo.
