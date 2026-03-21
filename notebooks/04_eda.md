# `04_eda.ipynb`

## Navegação do notebook

- [Início](../README.md)
- [Índice dos notebooks](README.md)
- [Anterior: feature engineering](03_feature_engineering.md)
- [Próximo: não supervisionado](05_unsupervised.md)
- [Dados processados](../data/processed/README.md)
- [Relatórios de EDA](../reports/eda/README.md)
- [Figuras](../reports/figures/README.md)

## Objetivo

Entender a distribuição dos dados, suas relações principais e possíveis problemas de qualidade.

## Entradas esperadas

- base processada em `data/processed/`;
- dicionário de variáveis ou descrição mínima dos atributos.

## Saídas esperadas

- estatísticas descritivas;
- distribuições das principais variáveis;
- correlações e padrões iniciais;
- identificação de outliers, ruído e desequilíbrios.

## Perguntas orientadoras

- quais atributos variam mais entre cenas e janelas?
- há padrões que indiquem separação natural de comportamentos?
- quais problemas de qualidade precisam ser tratados antes da modelagem?

## Critério de pronto

O notebook está pronto quando produzir insumos claros para orientar seleção de atributos e próximos experimentos.
