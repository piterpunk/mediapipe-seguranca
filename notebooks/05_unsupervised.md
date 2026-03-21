# `05_unsupervised.ipynb`

## Navegação do notebook

- [Início](../README.md)
- [Índice dos notebooks](README.md)
- [Anterior: EDA](04_eda.md)
- [Próximo: supervisionado](06_supervised.md)
- [Dados processados](../data/processed/README.md)
- [Resultados de modelagem](../reports/models/README.md)
- [Figuras](../reports/figures/README.md)

## Objetivo

Explorar agrupamentos e identificar possíveis eventos fora do padrão sem depender de rótulos prévios.

## Entradas esperadas

- base processada;
- conjunto de features selecionadas para clusterização e anomalias.

## Saídas esperadas

- agrupamentos de janelas ou cenas;
- scores de anomalia;
- interpretação dos perfis encontrados;
- comparação entre abordagens não supervisionadas.

## Perguntas orientadoras

- existem perfis naturais de comportamento nas cenas?
- quais janelas aparecem como fora do padrão?
- como traduzir os clusters em narrativa útil para a defesa?

## Critério de pronto

O notebook está pronto quando apresentar agrupamentos interpretáveis e anomalias defensáveis no contexto do problema.
