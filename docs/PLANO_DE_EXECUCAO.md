# Plano de execução

Este documento organiza o desenvolvimento do projeto em etapas práticas, conectando implementação, análise e material de apresentação.

## Navegação

- [Início](../README.md)
- [Contribuição](../CONTRIBUTING.md)
- [Arquitetura](ARQUITETURA.md)
- [Entregáveis](ENTREGAVEIS.md)
- [Roadmap](ROADMAP.md)
- [Dicionário de dados](DICIONARIO_DE_DADOS.md)
- [Dados](../data/README.md)
- [Notebooks](../notebooks/README.md)
- [Relatórios](../reports/README.md)

## Etapa 1: fundação do repositório

**Objetivo**: garantir uma base organizada e executável.

### Saídas esperadas

- estrutura de diretórios criada;
- `README.md` consolidado;
- package inicial em `src/mediapipe_seguranca/`;
- teste básico validando a pipeline inicial.

## Etapa 2: ingestão e percepção

**Objetivo**: sair da simulação e entrar na leitura real de vídeo.

### Itens de trabalho

- definir formato dos vídeos de entrada;
- ler vídeo quadro a quadro;
- integrar detectores e landmarks do MediaPipe;
- salvar saídas intermediárias com rastreabilidade.

### Evidências esperadas

- script funcional de leitura;
- exemplos de features extraídas;
- documentação da estrutura de colunas.

## Etapa 3: engenharia de atributos

**Objetivo**: transformar sinais visuais em variáveis úteis para análise.

### Itens de trabalho

- consolidar atributos por frame;
- agregar atributos por janela temporal;
- documentar variáveis e escalas;
- revisar consistência dos dados.

### Evidências esperadas

- base processada em `data/processed/`;
- descrição dos atributos utilizados;
- exemplos de séries temporais e janelas.

## Etapa 4: EDA e estatística

**Objetivo**: entender comportamento, distribuição e padrões iniciais dos dados.

### Itens de trabalho

- distribuição das variáveis;
- correlação entre atributos;
- análise de outliers e missing;
- gráficos temporais e ocupacionais.

### Evidências esperadas

- notebook de EDA;
- gráficos salvos em `reports/figures/`;
- síntese interpretativa em `reports/eda/`.

## Etapa 5: modelagem analítica

**Objetivo**: comparar abordagens supervisionadas e não supervisionadas.

### Itens de trabalho

- clusterização e detecção de anomalias;
- classificação de eventos rotulados;
- comparação de métricas;
- análise de erros e limitações.

### Evidências esperadas

- notebook ou script por abordagem;
- métricas registradas;
- resumo analítico em `reports/models/`.

## Etapa 6: consolidação de defesa

**Objetivo**: transformar os resultados em narrativa de apresentação.

### Itens de trabalho

- selecionar figuras-chave;
- organizar achados principais;
- registrar limitações e riscos metodológicos;
- montar roteiro de defesa.

### Evidências esperadas

- material em `reports/defesa/`;
- argumento técnico alinhado ao problema de pesquisa;
- encadeamento claro entre hipótese, método, resultado e conclusão.

## Definição de pronto por frente

- **Código**: executa sem ajustes manuais fora do fluxo documentado.
- **Dados**: possuem origem e etapa identificáveis.
- **Análise**: contém explicação, não apenas gráfico ou métrica.
- **Modelagem**: registra critérios de avaliação e interpretação.
- **Defesa**: conecta resultados ao objetivo do projeto.
