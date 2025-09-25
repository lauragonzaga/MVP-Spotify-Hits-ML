# MVP: Predição de Popularidade de Faixas no Spotify

Trabalho realizado para a sprint de Machine Learning & Analytics do curso de pós-graduação em Ciência de Dados & Analytics da PUC-Rio.

Você pode conferir o notebook [clicando aqui](https://github.com/lauragonzaga/MVP-Spotify-Hits-ML/blob/main/MVP_Spotify_Tracks.ipynb).

## Descrição do projeto
Este projeto tem como objetivo estimar a probabilidade de uma música se tornar um **hit** no Spotify (popularidade ≥ 70).  
A proposta é apoiar decisões em áreas como **marketing** e **curadoria de playlists**, ajudando a priorizar faixas para promoção.  

Utilizamento o conjunto de dados [Spotify Music Dataset](https://www.kaggle.com/datasets/solomonameh/spotify-music-dataset) — disponível no Kaggle — que reúne atributos musicais já extraídos pela API da plataforma.

---

## O que foi feito
- **Limpeza e preparação dos dados** (remoção de duplicados, tratamento de nulos, renomeação de variáveis).  
- **Engenharia de atributos** (conversão de duração para minutos, extração de ano de lançamento).  
- **EDA (análise exploratória)** para identificar padrões de popularidade e diferenças entre hits e não-hits.
- **Construção de pipelines de pré-processamento e modelagem**, garantindo reprodutibilidade e evitando vazamento de dados. 
- **Modelagem supervisionada** com três algoritmos: Logistic Regression, Random Forest e XGBoost.  
- **Validação cruzada estratificada** e comparação com baseline.  
- **Métricas de avaliação** com foco em PR-AUC e recall, dado desbalanceamento das classes.  
- **GridSearchCV** para ajuste de hiperparâmetros do XGBoost.  
- **Conclusões e próximos passos** discutindo aplicações e limitações.  

---

## Ferramentas e bibliotecas
- Python (pandas, numpy, scikit-learn, xgboost)  
- Visualização: seaborn, matplotlib  
- Reprodutibilidade e cache: joblib, json  
- Ambiente: Google Colab  

---
