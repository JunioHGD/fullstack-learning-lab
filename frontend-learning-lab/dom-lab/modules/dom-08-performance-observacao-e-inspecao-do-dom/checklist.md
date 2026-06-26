# Checklist — DOM-08: Performance, observação e inspeção do DOM
## Objetivo do módulo

Ensinar o DOM como estrutura com custo de renderização, superfície observável e objeto de depuração profissional.
## Progresso por tópico
### DOM-08.01 — Custo do tamanho do DOM
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-08.01.01 — Tamanho, profundidade e complexidade do DOM
  - [ ] Compreendi: Reconhecer o tamanho do DOM como fator de custo em páginas reais.
  - [ ] Consigo demonstrar: Evitar estruturas excessivamente grandes ou profundas sem necessidade.

### DOM-08.02 — Impacto de mudanças no pipeline visual
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-08.02.01 — Mudanças de DOM em style, layout e paint
  - [ ] Compreendi: Entender que diferentes alterações podem disparar trabalhos diferentes no navegador.
  - [ ] Consigo demonstrar: Classificar alterações simples como potencialmente baratas ou custosas em termos de renderização.

### DOM-08.03 — Reflow e layout thrashing
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-08.03.01 — Reflow, layout thrashing e leitura/escrita frequente
  - [ ] Compreendi: Identificar alternância problemática entre leituras de layout e escritas no DOM.
  - [ ] Consigo demonstrar: Reconhecer padrões que podem degradar a fluidez de interação.

### DOM-08.04 — Atualização em lote
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-08.04.01 — Estratégias de atualização em lote
  - [ ] Compreendi: Planejar múltiplas alterações antes de aplicá-las ao DOM principal.
  - [ ] Consigo demonstrar: Organizar renderizações dinâmicas com menor custo estrutural.

### DOM-08.05 — Observação de mutações
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-08.05.01 — MutationObserver
  - [ ] Compreendi: Criar observadores para reagir a inserções, remoções e alterações no DOM.
  - [ ] Consigo demonstrar: Saber quando observar mudanças é útil e quando pode indicar arquitetura inadequada.

### DOM-08.06 — Inspeção da árvore DOM no DevTools
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-08.06.01 — Elements Panel e árvore DOM
  - [ ] Compreendi: Navegar pela árvore DOM real do navegador no DevTools.
  - [ ] Consigo demonstrar: Localizar elementos, inspecionar hierarquia e entender alterações temporárias no DevTools.

### DOM-08.07 — Depuração de eventos e mutações
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-08.07.01 — Event Listeners, Properties e DOM breakpoints
  - [ ] Compreendi: Usar ferramentas do DevTools para identificar listeners e pausar em alterações do DOM.
  - [ ] Consigo demonstrar: Depurar quem está ouvindo eventos ou alterando elementos da interface.

### DOM-08.08 — Inspeção de acessibilidade e gargalos
- [ ] Li o `README.md` do tópico.
- [ ] Estudei o arquivo `lessons.md`.
- [ ] Respondi às perguntas de assimilação.
- [ ] Pratiquei ou planejei exercícios em `exercises/`.
#### Aulas
- [ ] DOM-08.08.01 — Accessibility tab, source order, foco e gargalos de interação
  - [ ] Compreendi: Inspecionar propriedades acessíveis e sinais de problemas de interação.
  - [ ] Consigo demonstrar: Validar aspectos básicos de acessibilidade e interação usando DevTools.

## Fechamento do módulo

- [ ] Revisei todos os tópicos do módulo.
- [ ] Revisei as principais dúvidas registradas.
- [ ] Respondi às perguntas de entrevista em `interview-questions.md`.
- [ ] Criei ou planejei o projeto em `docs/projects/dom-08-performance-observacao-e-inspecao-do-dom/`.
- [ ] Documentei aprendizados importantes antes de avançar para o próximo módulo.
