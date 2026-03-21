# Entregáveis do projeto

Este documento refina os entregáveis previstos para o projeto e organiza o que deve ser produzido, onde será armazenado e como cada item poderá ser validado.

## Navegação

- [Início](../README.md)
- [Contribuição](../CONTRIBUTING.md)
- [Arquitetura](ARQUITETURA.md)
- [Plano de execução](PLANO_DE_EXECUCAO.md)
- [Roadmap](ROADMAP.md)
- [Dicionário de dados](DICIONARIO_DE_DADOS.md)
- [Dados](../data/README.md)
- [Notebooks](../notebooks/README.md)
- [Relatórios](../reports/README.md)

## Objetivo deste documento

Padronizar a evolução do repositório para que o projeto avance com clareza técnica e coerência acadêmica, separando os artefatos por natureza e por etapa de maturidade.

## Matriz de entregáveis

| Frente | Entregável | Descrição | Local previsto | Critério de aceite |
| --- | --- | --- | --- | --- |
| Estrutura | Repositório organizado | Estrutura mínima com código, dados, notebooks, relatórios e documentação | Raiz do projeto | Pastas e arquivos coerentes com a pipeline |
| Dados | Base bruta | Vídeos e insumos originais autorizados | `data/raw/` | Arquivos identificados e documentados |
| Dados | Base intermediária | Saídas parciais da extração e preparação | `data/interim/` | Arquivos rastreáveis por etapa |
| Dados | Base processada | Features por frame e por janela | `data/processed/` | Dataset pronto para análise e modelagem |
| Dados | Rótulos | Classes e anotações de eventos | `data/labels/` | Convenção de rótulos documentada |
| Engenharia | Pipeline de ingestão | Leitura e organização de vídeo | `src/mediapipe_seguranca/video_io.py` | Execução reprodutível |
| Engenharia | Extração visual | Camada de percepção com MediaPipe | `src/mediapipe_seguranca/mediapipe_extract.py` | Features visuais geradas com consistência |
| Engenharia | Feature engineering | Consolidação de atributos analíticos | `src/mediapipe_seguranca/feature_engineering.py` | Features úteis e documentadas |
| Análise | EDA | Estatística descritiva, distribuição e correlação | `notebooks/` e `reports/eda/` | Visualizações e interpretação coerentes |
| Modelagem | Não supervisionado | Clusterização e detecção de anomalias | `src/` e `reports/models/` | Resultados analisáveis e comparáveis |
| Modelagem | Supervisionado | Classificação de eventos rotulados | `src/` e `reports/models/` | Métricas e avaliação registradas |
| Comunicação | Figuras | Gráficos, heatmaps e imagens de apoio | `reports/figures/` | Material reutilizável na defesa |
| Comunicação | Defesa | Slides, roteiro e síntese dos resultados | `reports/defesa/` | Narrativa técnica alinhada ao projeto |

## Pacotes de entrega

### Pacote 1: fundação técnica

- estrutura inicial do repositório;
- pipeline base executável;
- contrato inicial de diretórios de dados;
- documentação de navegação do projeto.

### Pacote 2: extração e dados analíticos

- leitura real de vídeo;
- integração com MediaPipe;
- geração de features por frame e por janela;
- rastreamento dos arquivos gerados.

### Pacote 3: análise e modelagem

- notebooks de EDA;
- análise estatística e visual;
- resultados supervisionados;
- resultados não supervisionados;
- comparação entre abordagens.

### Pacote 4: consolidação acadêmica

- relatórios finais de interpretação;
- seleção de figuras para apresentação;
- roteiro de defesa;
- síntese dos achados, limitações e próximos passos.

## Critérios transversais

- **Organização**: cada artefato deve estar na pasta adequada.
- **Clareza**: nomes de arquivos devem indicar propósito e etapa.
- **Reprodutibilidade**: o caminho de geração do artefato deve ser identificável.
- **Consistência**: documentação e estrutura devem evoluir juntas.
- **Defensabilidade**: resultados precisam ser interpretáveis em contexto acadêmico.

## Prioridade atual

No momento, a prioridade recomendada é avançar nos seguintes itens:

1. formalizar o contrato de dados e rótulos;
2. integrar leitura real de vídeo;
3. substituir extração simulada por extração real com MediaPipe;
4. iniciar notebooks de EDA;
5. abrir a trilha de relatórios em `reports/`.
