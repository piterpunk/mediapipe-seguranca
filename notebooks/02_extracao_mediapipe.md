# `02_extracao_mediapipe.ipynb`

## Navegação do notebook

- [Início](../README.md)
- [Índice dos notebooks](README.md)
- [Anterior: ingestão](01_ingestao.md)
- [Próximo: feature engineering](03_feature_engineering.md)
- [Dados intermediários](../data/interim/README.md)
- [Arquitetura](../docs/ARQUITETURA.md)
- [Dicionário de dados](../docs/DICIONARIO_DE_DADOS.md)

## Objetivo

Explorar a camada de percepção com MediaPipe e verificar a viabilidade da extração de sinais visuais relevantes.

## Entradas esperadas

- amostras de vídeo ou frames vindos da ingestão;
- configuração de tasks do MediaPipe;
- recortes de teste para inspeção visual.

## Saídas esperadas

- exemplos de detecções e landmarks;
- análise qualitativa da estabilidade da extração;
- estrutura preliminar de colunas derivadas da percepção;
- notas sobre limitações e ajustes necessários.

## Perguntas orientadoras

- quais tasks do MediaPipe geram sinais mais úteis para o problema?
- a extração é estável em diferentes condições de cena?
- quais atributos já podem ser consolidados para a próxima etapa?

## Critério de pronto

O notebook está pronto quando evidenciar quais sinais extraídos entram na engenharia de atributos e como eles serão persistidos.
