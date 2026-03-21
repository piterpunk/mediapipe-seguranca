# `06_supervised.ipynb`

## Navegação do notebook

- [Início](../README.md)
- [Índice dos notebooks](README.md)
- [Anterior: não supervisionado](05_unsupervised.md)
- [Próximo: visualizações](07_visualizacoes.md)
- [Dados processados](../data/processed/README.md)
- [Rótulos](../data/labels/README.md)
- [Resultados de modelagem](../reports/models/README.md)

## Objetivo

Treinar e comparar classificadores para distinguir eventos rotulados de interesse.

## Entradas esperadas

- base processada;
- rótulos consolidados em `data/labels/`;
- conjunto de features selecionadas.

## Saídas esperadas

- divisão de treino, validação e teste;
- métricas por modelo;
- matrizes de confusão e análise de erros;
- interpretação dos resultados com foco acadêmico.

## Perguntas orientadoras

- os atributos extraídos distinguem bem os eventos previstos?
- quais modelos entregam melhor compromisso entre desempenho e interpretabilidade?
- quais erros são mais críticos para o contexto do projeto?

## Critério de pronto

O notebook está pronto quando houver comparação consistente entre modelos e leitura crítica das métricas obtidas.
