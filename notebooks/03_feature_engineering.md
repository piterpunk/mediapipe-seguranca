# `03_feature_engineering.ipynb`

## Navegação do notebook

- [Início](../README.md)
- [Índice dos notebooks](README.md)
- [Anterior: extração com MediaPipe](02_extracao_mediapipe.md)
- [Próximo: EDA](04_eda.md)
- [Dados processados](../data/processed/README.md)
- [Dicionário de dados](../docs/DICIONARIO_DE_DADOS.md)
- [Código-fonte](../src/README.md)

## Objetivo

Transformar os sinais extraídos em atributos analíticos utilizáveis em EDA e modelagem.

## Entradas esperadas

- saídas intermediárias da extração;
- tabela por frame ou segmento;
- regras de agregação temporal.

## Saídas esperadas

- features por frame;
- features agregadas por janela;
- definição de nomes, tipos e interpretação das variáveis;
- versão inicial da base processada.

## Perguntas orientadoras

- quais atributos capturam ocupação, movimento e risco?
- como resumir informação temporal sem perder interpretabilidade?
- quais colunas entram como candidatas para modelagem?

## Critério de pronto

O notebook está pronto quando gerar uma base analítica coerente, documentada e reaproveitável fora do notebook.
