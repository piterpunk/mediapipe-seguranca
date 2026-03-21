# `01_ingestao.ipynb`

## Navegação do notebook

- [Início](../README.md)
- [Índice dos notebooks](README.md)
- [Próximo: extração com MediaPipe](02_extracao_mediapipe.md)
- [Dados brutos](../data/raw/README.md)
- [Arquitetura](../docs/ARQUITETURA.md)
- [Relatórios](../reports/README.md)

## Objetivo

Validar a leitura dos vídeos, a organização dos frames e a estrutura temporal mínima para a pipeline.

## Entradas esperadas

- arquivos em `data/raw/`;
- metadados de vídeo, quando disponíveis;
- parâmetros iniciais de amostragem e janelamento.

## Saídas esperadas

- inspeção básica dos vídeos;
- tabela com metadados de frames ou segmentos;
- validação do esquema de janelas temporais;
- observações sobre qualidade e consistência dos insumos.

## Perguntas orientadoras

- quais vídeos estão disponíveis e em que formato?
- qual é a granularidade temporal ideal para a análise?
- há problemas de qualidade, duração ou padronização?

## Critério de pronto

O notebook está pronto quando demonstrar leitura reproduzível dos dados brutos e registrar a estratégia de segmentação temporal.
