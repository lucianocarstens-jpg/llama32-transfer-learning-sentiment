# Classificação de Sentimentos com Llama 3.2 1B

Projeto desenvolvido na especialização em Inteligência Artificial Generativa (GENAI2026), utilizando Transfer Learning com o modelo Llama 3.2 1B para classificação de sentimentos em avaliações de filmes.

## Objetivo

Explorar a utilização de um Large Language Model (LLM) pré-treinado para classificação de sentimentos, aproveitando suas representações internas e treinando uma camada classificadora.

## Tecnologias utilizadas

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Llama 3.2 1B
- Google Colab com GPU NVIDIA T4
- Scikit-learn
- Matplotlib e Seaborn

## Dataset

Foi utilizado o dataset IMDb, contendo avaliações de filmes classificadas em sentimentos positivos e negativos.

Amostras utilizadas no experimento:
- Treinamento: 400 avaliações
- Teste: 100 avaliações

## Metodologia

1. Carregamento do modelo Llama 3.2 1B.
2. Tokenização das avaliações.
3. Extração das representações internas do modelo (Hidden States).
4. Geração de vetores de características.
5. Treinamento de uma camada classificadora utilizando PyTorch.
6. Avaliação do desempenho com métricas de classificação.

## Resultados

Acurácia obtida no conjunto de teste:

**76% (76 acertos em 100 avaliações).**

O experimento também gerou matriz de confusão e relatório de classificação, permitindo analisar precisão, recall e F1-score para cada classe.

## Autor

**Luciano Carstens**

Especialização em Inteligência Artificial Generativa – GENAI2026.
