# ADR-001 — Adoção da stack e diretrizes tecnológicas iniciais

- **Situação:** proposta
- **Data:** 2026-10-23
- **Participantes:** Tiago Santos e equipe

## Contexto

Precisamos estabelecer a stack tecnológica e a base inicial de organização do código para iniciar o desenvolvimento do projeto, mantendo agilidade e suporte eficiente de ferramentas de IA, com a flexibilidade de refinar a arquitetura conforme o projeto evoluir.

## Decisão

Adotar o NestJS com TypeScript no back-end e React com TypeScript no front-end como fundação inicial, mantendo a flexibilidade de estruturação (monolito modular) enquanto a equipe consolida os requisitos funcionais.

## Alternativas consideradas

| Alternativa | Por que não foi escolhida |
|---|---|
| Linguagem sem tipagem estática (JavaScript puro) | Menor confiabilidade e maior dificuldade de manutenção e suporte por IA em escala. |
| Tecnologias sem padronização estrutural | Exigiriam maior esforço manual na configuração inicial que o ecossistema escolhido já resolve. |

## Consequências

- **Positivas:** Agilidade inicial com suporte de IA, tipagem estática robusta e facilidade de padronização.
- **Negativas:** Possível necessidade de ajustes arquiteturais futuros caso a complexidade do projeto mude de rumo.
- **Como verificar:** Revisões de código, pull requests e testes automatizados.
