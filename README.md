# Tabela Brasileira de Composição de Alimentos (TBCA)

Este é um arquivo SQLite contendo todos os alimentos da TBCA.

## Fonte

https://www.tbca.net.br/

## Estrutura

Cada alimento possui

- Código
- Nome
- Nome científico
- Grupo
- Marca
- Nutrientes em 100g
- Campo chamado "Outros valores", que são porções específicas daquele alimento divididas por 100g. Exemplo:

```json
[{ "label": "Colher sopa cheia (36 g)", "value": "0.36" }]
```

## Nota

[Este alimento](https://www.tbca.net.br/base-dados/int_composicao_alimentos.php?cod_produto=BRC0262C) não possui valores no site, portanto foi removido.
