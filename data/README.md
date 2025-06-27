# Bases de Dados Utilizadas

Aqui estão reunidas as bases de dados públicas utilizadas em estudos e atividades de Ciência de Dados. A maioria dos conjuntos está disponível para download no [Kaggle](https://www.kaggle.com/datasets). Entretanto, alguns datasets foram obtidos diretamente dos autores dos artigos e, portanto, não estão no Kaggle. Para esses casos, disponibilizamos o acesso via Google Drive.

## Acesso às Bases no Google Drive

As bases de dados não disponíveis no Kaggle _muito provavelmente_ podem ser encontradas nas seguintes pastas do Google Drive:

1. [Bases de Dados - Pasta 1](https://drive.google.com/drive/folders/1HmdzPslXIvonThOhICcPPS6Y-rzojfTJ?usp=sharing)
2. [Bases de Dados - Pasta 2](https://drive.google.com/drive/folders/19A2EeX_NTU4-67kEd2VO9Xy-M4uUAn9T?usp=sharing)

## Atividades

### Regressão Linear

- **California Housing Dataset**: Utilizado na atividade de regressão linear para prever valores de casas
  - `databaseCasas.csv` - Conjunto de treinamento
  - `databaseCasasTest.csv` - Conjunto de teste
  - Também disponível via: `from sklearn.datasets import fetch_california_housing`

### Classificação

- **Titanic Dataset**: Utilizado na atividade de aprendizado de máquina para classificação de sobreviventes
  - `databaseTitanic.csv` - Conjunto de treinamento
  - `databaseTitanicTest.csv` - Conjunto de teste
  - [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

### Análise Exploratória

- Consulte os notebooks `Analise_Exploratoria.ipynb`, `Analise-Exploratoria-Financeira.ipynb` e `Analise-Exploratoria-Parte2.ipynb` para detalhes sobre os datasets utilizados nestas atividades.

### Aprendizado Não Supervisionado

- **Iris Dataset**: Utilizado na atividade de clustering com K-Means
  - `databaseIris.csv` - Dataset clássico com medidas de pétalas e sépalas de íris
  - Também disponível via: `from sklearn.datasets import load_iris`
  - Consulte o notebook `K_Means_Aprendizado_Nao_Supervisionado.ipynb` para detalhes

### Sistema de Recomendação

- **IMDB Movies Dataset**: Utilizado para sistema de recomendação de filmes
  - `databaseIMDB.csv` - Dataset com informações de filmes e avaliações
  - Consulte os notebooks `SistemaRecomendacaoPythonCEUB_KNN.ipynb` e `SistemaRecomendacaoPythonCEUB_KNN_e_KMeans.ipynb`

---

> **Atenção:**  
> Se não encontrar o dataset desejado no Kaggle, consulte a seção [Acesso às Bases no Google Drive](#acesso-às-bases-no-google-drive).

## Estudos de Caso

### Estudo de Caso 1: Detecção de Transações Fraudulentas

- [Kaggle - Fraud Transaction Detection](https://www.kaggle.com/code/llabhishekll/fraud-transaction-detection/input)
- Google Drive - _databaseFraude_ nas [pastas do Google Drive](#acesso-às-bases-no-google-drive)

### Estudo de Caso 2: Previsão de Cancelamento de Reservas em Hotéis

- [Kaggle - Hotel Booking](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand/data)
- Google Drive - _databaseHotel_ nas [pastas do Google Drive](#acesso-às-bases-no-google-drive)

### Estudo de Caso 3

#### Parte 1: Recomendação de Preços de Aluguel de Apartamentos

- Google Drive - _databaseApartamentos_ nas [pastas do Google Drive](#acesso-às-bases-no-google-drive)

#### Parte 2: Análise de Fatores que Influenciam o Número de Óbitos por Covid-19

- Google Drive - _databaseCovid_ nas [pastas do Google Drive](#acesso-às-bases-no-google-drive)

### Estudo de Caso 4: Sistema de Recomendação de Produtos Online

- [Kaggle - Amazon electronics Rating Dataset](https://www.kaggle.com/datasets/vibivij/amazon-electronics-rating-datasetrecommendation)
- Google Drive - _databaseEletronicos_ nas [pastas do Google Drive](#acesso-às-bases-no-google-drive)

### Estudo de Caso 5: Análise e Classificação de Flores Iris

- **Iris Dataset**: Dataset clássico para análise de classificação multiclasse
  - `databaseIris.csv` - Dataset com características morfológicas de três espécies de íris
  - [Kaggle - Iris Species](https://www.kaggle.com/datasets/uciml/iris)
  - Também disponível via: `from sklearn.datasets import load_iris`

### Estudo de Caso 6: Sistema de Recomendação e Análise de Filmes

- **IMDB Movies Dataset**: Base de dados abrangente sobre filmes e avaliações
  - `databaseIMDB.csv` - Dataset com informações detalhadas de filmes, gêneros, avaliações e metadados
  - [Kaggle - IMDB Movie Dataset](https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows)
  - Google Drive - _databaseIMDB_ nas [pastas do Google Drive](#acesso-às-bases-no-google-drive)

---

> **Atenção:**  
> Se não encontrar o dataset desejado no Kaggle, consulte a seção [Acesso às Bases no Google Drive](#acesso-às-bases-no-google-drive).
