# Dados do projeto

Este diretório concentra os artefatos de dados usados ao longo da pipeline.

- `raw/`: vídeos originais ou arquivos brutos de entrada.
- `interim/`: saídas intermediárias de extração e preparação.
- `processed/`: bases finais para análise e modelagem.
- `labels/`: rótulos e anotações de eventos.

## Convenção de uso

- arquivos em `raw/` devem preservar a origem original do dado;
- arquivos em `interim/` devem representar transformações intermediárias reproduzíveis;
- arquivos em `processed/` devem estar prontos para EDA ou modelagem;
- arquivos em `labels/` devem explicitar a taxonomia de eventos usada no projeto.

## Observações importantes

- os arquivos gerados automaticamente pela demo local não devem ser versionados;
- sempre que uma nova base for criada, a documentação deve indicar como ela foi produzida;
- a separação entre dado bruto e dado derivado deve ser mantida para facilitar auditoria e defesa.
