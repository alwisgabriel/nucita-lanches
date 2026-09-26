# Mapa entre GitHub Issues e Trello

Este arquivo deve ser usado até que as Issues sejam criadas diretamente no GitHub. Depois da criação, substitua “a criar” pelo número e pelo link real da Issue.

## Listas do Trello

1. **Backlog** — ideias e tarefas ainda não priorizadas.
2. **A fazer** — tarefas escolhidas para execução.
3. **Em desenvolvimento** — tarefa em uma branch.
4. **Em revisão** — tarefa com Pull Request aberto.
5. **Bloqueado** — tarefa aguardando decisão ou dependência.
6. **Concluído** — Issue encerrada e PR integrado.

## Cartões iniciais

| Cartão do Trello | Issue | Prioridade | Dependência |
|---|---|---:|---|
| Validar requisitos e regras de negócio | a criar — `ISSUE-01` | Alta | Nenhuma |
| Criar DER | a criar — `ISSUE-02` | Alta | `ISSUE-01` |
| Criar Diagrama de Classes | a criar — `ISSUE-03` | Alta | `ISSUE-01` |
| Criar Casos de Uso | a criar — `ISSUE-04` | Alta | `ISSUE-01` |
| Produtos do cardápio | a criar — `ISSUE-05` | Alta | `ISSUE-01`, `ISSUE-03` |
| Mesas do restaurante | a criar — `ISSUE-06` | Alta | `ISSUE-01`, `ISSUE-03` |
| Abrir pedido | a criar — `ISSUE-07` | Alta | `ISSUE-06` |
| Adicionar itens ao pedido | a criar — `ISSUE-08` | Alta | `ISSUE-05`, `ISSUE-07` |
| Cálculo do pedido | a criar — `ISSUE-09` | Alta | `ISSUE-08` |
| Alterar itens do pedido | a criar — `ISSUE-10` | Média | `ISSUE-08`, `ISSUE-09` |
| Finalizar pedido | a criar — `ISSUE-11` | Alta | `ISSUE-09`, `ISSUE-10` |
| Validações e erros | a criar — `ISSUE-12` | Alta | `ISSUE-05` a `ISSUE-11` |
| Testes | a criar — `ISSUE-13` | Média | `ISSUE-05` a `ISSUE-12` |
| README e entrega final | a criar — `ISSUE-14` | Alta | Todas as anteriores |

## Modelo de cartão

```markdown
## Objetivo

[Resumo da issue]

## Issue do GitHub

Número/link: a criar

## Critérios de aceite

- [ ] Critério 1
- [ ] Critério 2

## Branch

`tipo/nome-da-tarefa`

## Observações

Registrar decisões, bloqueios e links para Pull Requests.
```

## Como sincronizar

1. Criar a Issue usando o texto de `BACKLOG.md`.
2. Copiar o link da Issue para este arquivo.
3. Criar um cartão com o mesmo título no Trello.
4. Adicionar o link da Issue no cartão.
5. Mover o cartão conforme o estado da tarefa.
6. Adicionar o link do PR quando a implementação começar.
