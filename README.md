# DL-SentimentAnalysis-Headline-News

### Sobre os arquivos de treino dos modelos:
- Para cada Embedding, criou-se um arquivo ipynb, resultando assim em três arquivos.
- Os Embeddings utilizados foram obtidos a partir do NILC-NLP-Collections do Hugging Face (https://huggingface.co/collections/nilc-nlp/nilc-embeddings)
- Foram utlizados os Embeddings de 50 dimensões paraa o Word2Vec e GloVe

A metodologia de execução foi igual para as três abordagens:
- Pré-processamento
- Representação Textual das Manchetes via Embedding
- Construção da arquitetura dos modelos
- Validação cruzada com combinações de hiperparâmetros
- Treino e Teste do modelo final com a melhor commbinação de hiperparâmetros

### Sobre o dataset:
- 8638 registros de manchetes de notícias sobre a Politec predominantemente dos anos de 2023 e 2024
- 6 sites de notícias estaduais
- três classes (0 = negativo ; 1 = neutro ; 2 = positivo)
