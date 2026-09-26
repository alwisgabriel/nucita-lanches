# Planejamento da Entrega — Nucita Lanches

## Situação atual

O projeto está sendo desenvolvido em Java e possui uma branch de trabalho chamada:

```text
feat/cadastro-produtos-e-mesas
```

As classes identificadas são:

- `Produto`
- `Mesa`
- `Pedido`
- `ItemPedido`

O sistema representa pedidos realizados em mesas de uma lanchonete/restaurante.

## Regras de negócio identificadas

- Uma mesa pode possuir vários pedidos ao longo do tempo.
- Cada pedido pertence a uma mesa.
- Um pedido possui vários itens.
- Cada item possui um produto e uma quantidade.
- O subtotal é calculado pelo preço do produto multiplicado pela quantidade.
- O total do pedido é a soma dos subtotais.
- Remover um item deve atualizar o total.
- Um pedido finalizado não pode ser alterado.

## Entregas acadêmicas

1. Diagrama de Entidade-Relacionamento.
2. Diagrama de Classes.
3. Diagrama de Casos de Uso.
4. Backend completo.
5. README e documentação da execução.

## Backlog inicial

### Análise e modelagem

- Levantar requisitos funcionais e não funcionais.
- Validar as regras de negócio com o grupo.
- Criar o DER.
- Criar o Diagrama de Classes.
- Criar o Diagrama de Casos de Uso.

### Produtos

- Definir cadastro de produtos.
- Definir consulta de produtos.
- Definir alteração e disponibilidade de produtos.
- Validar nome e preço.

### Mesas

- Definir cadastro de mesas.
- Consultar mesas existentes.
- Associar pedidos às mesas.

### Pedidos

- Abrir pedido para uma mesa.
- Adicionar produto ao pedido.
- Alterar quantidade de item.
- Remover item do pedido.
- Consultar pedido e seus itens.
- Calcular subtotal e total.
- Finalizar pedido.
- Impedir alterações em pedido finalizado.

### Qualidade e entrega

- Criar validações para situações inválidas.
- Criar testes das regras de negócio.
- Revisar encapsulamento e responsabilidades das classes.
- Atualizar README.
- Conferir coerência entre requisitos, diagramas e código.

## Estratégia de branches

- `main`: versão estável do projeto.
- `feat/cadastro-produtos-e-mesas`: branch de desenvolvimento existente.
- `chore/planejamento-entrega`: branch atual para documentação e planejamento.
- Futuras funcionalidades devem ser desenvolvidas em branches próprias e enviadas por Pull Request.

## Próxima etapa

Validar este planejamento com o grupo antes de implementar código. Depois da validação, criar as issues no GitHub, detalhar os diagramas e iniciar a implementação por pequenas Pull Requests.

