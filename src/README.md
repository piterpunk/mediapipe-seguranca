# Estrutura do código-fonte

O diretório `src/` concentra a implementação do projeto em formato modular.

## Navegação

- [Início](../README.md)
- [Contribuição](../CONTRIBUTING.md)
- [Arquitetura](../docs/ARQUITETURA.md)
- [Dicionário de dados](../docs/DICIONARIO_DE_DADOS.md)
- [Notebooks](../notebooks/README.md)
- [Dados](../data/README.md)
- [Testes](../tests/README.md)

## Módulos atuais

- `mediapipe_seguranca/video_io.py`: ingestão e metadados de vídeo.
- `mediapipe_seguranca/mediapipe_extract.py`: camada de extração visual.
- `mediapipe_seguranca/tracking_features.py`: enriquecimento dos sinais extraídos.
- `mediapipe_seguranca/feature_engineering.py`: agregação e consolidação de atributos.
- `mediapipe_seguranca/train_unsupervised.py`: baseline não supervisionado.
- `mediapipe_seguranca/train_supervised.py`: baseline supervisionado.
- `mediapipe_seguranca/evaluate.py`: sumarização de resultados.
- `mediapipe_seguranca/pipeline.py`: orquestração da pipeline inicial.

## Diretriz de evolução

- lógica reutilizável deve ficar em `src/`;
- notebooks não devem concentrar regras centrais da pipeline;
- novos módulos devem refletir etapas reais do projeto e manter responsabilidade única.
