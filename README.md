# PUC_ML
Trabalho para a sprint Machine Learning da pós-graduação em Ciência de Dados da PUC Rio.

# Classificação de Gêneros Musicais com Machine Learning

## Objetivo

Este projeto desenvolve e compara modelos de aprendizado de máquina para classificar músicas em gêneros musicais a partir de atributos acústicos do Spotify.

## Dataset

O conjunto de dados inicial continha 114.000 músicas distribuídas em 114 gêneros musicais. Para o estudo, um gênero que apresentava muitas faixas faladas foi excluído. A dase de dados está balanceada com 1000 faixas para cada gênero.

## Modelos avaliados

- DummyClassifier (baseline)
- KNN
- Gaussian Naive Bayes
- Decision Tree
- Random Forest

## Resultados

| Modelo | Accuracy | F1-weighted |
|---------|---------:|------------:|
| Baseline | 0.009 | 0.000 |
| KNN | 0.172 | 0.170 |
| GaussianNB | 0.060 | 0.034 |
| Decision Tree | 0.165 | 0.166 |
| Random Forest | **0.243** | **0.233** |

## Tecnologias

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab
