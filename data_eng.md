Install
- Docker
- python

AI -> dado deveria estar na camada mais refinada
RAG -> 

Particionar PDFs em chunks - > Polars
Se colapsar a RAM -> particionar por paginas
Se o modelo for local (HuggingFaces) -> pontos extras 

Raw(PDF) -> Domain/Silver (checkpoint) como .txt -> Gold .picle para armazenar os vetores

1. Primeiro processo a ser feito: tratar os dados
rexeg
estrutura do documento: titulo, ingredientes, instrucoes

2. Configuracao do DB: vector database
Embeddings: envia para API

DB: Postgres com a extensao PgVector

verificar o tamanho do vetor que retorna ???

3. Ingestao dos dados


4. Criacao de index

