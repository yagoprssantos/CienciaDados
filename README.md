# Ciência de Dados - Estudos e Atividades

Este repositório contém estudos de caso e atividades práticas em Ciência de Dados, focando em análise exploratória, modelagem preditiva e visualização de dados.

## 📁 Estrutura do Repositório

- `data/`: Contém as bases de dados utilizadas nos estudos e atividades.
- `notebooks/`: Jupyter Notebooks com análises e visualizações.
- `docs/`: Documentação com PDFs utilizados e relatórios.

## 📚 Atividades

As atividades estão organizadas abordando um aspecto específico da Ciência de Dados apresentado em cada aula.

### 1. Regressão Linear

> Análise e predição de valores de imóveis na Califórnia.

**Arquivos Relacionados:**

- 📓 [Notebook Principal](notebooks/atividades/Regressao_Linear.ipynb)
- 📊 [Base de Dados de Treinamento](data/databaseCasas.csv)
- 📊 [Base de Dados de Teste](data/databaseCasasTest.csv)

**Principais Técnicas Aplicadas:**

- Regressão Linear Simples e Múltipla
- Avaliação de modelos com métricas como R² e MSE
- Análise de resíduos e identificação de outliers

### 2. Classificação

> Predição de sobreviventes do naufrágio do Titanic.

**Arquivos Relacionados:**

- 📓 [Notebook Principal](notebooks/atividades/Classificacao.ipynb)
- 📊 [Base de Dados de Treinamento](data/databaseTitanic.csv)
- 📊 [Base de Dados de Teste](data/databaseTitanicTest.csv)

**Principais Técnicas Aplicadas:**

- Algoritmos de classificação (Árvores de Decisão, KNN, Regressão Logística)
- Feature engineering e seleção de variáveis
- Avaliação com matriz de confusão, acurácia e F1-score

### 3. Análise Exploratória de Dados

> Exploração visual e estatística de diferentes conjuntos de dados.

**Arquivos Relacionados:**

- 📓 [Análise Exploratória - Parte 1](notebooks/atividades/Analise_Exploratoria.ipynb)
- 📓 [Análise Exploratória Financeira](notebooks/atividades/Analise-Exploratoria-Financeira.ipynb)
- 📓 [Análise Exploratória - Parte 2](notebooks/atividades/Analise-Exploratoria-Parte2.ipynb)

**Principais Técnicas Aplicadas:**

- Visualização de dados com matplotlib e seaborn
- Análise estatística descritiva
- Identificação de correlações e padrões

### 4. Aprendizado Não Supervisionado

> Clustering e redução de dimensionalidade em conjuntos de dados.

**Arquivos Relacionados:**

- 📓 [Notebook K-Means](notebooks/atividades/K_Means_Aprendizado_Nao_Supervisionado.ipynb)

**Principais Técnicas Aplicadas:**

- Algoritmo K-Means para clustering
- Método do cotovelo para escolha do número ideal de clusters
- Visualização e interpretação de clusters

## 📊 Estudos de Caso

Os estudos de caso são projetos mais complexos que envolvem a aplicação de técnicas de Ciência de Dados em problemas reais. Cada estudo inclui análise exploratória, modelagem preditiva e visualização de dados.

### 1. Detecção de Transações Fraudulentas

> Desenvolvimento de modelos preditivos para identificação de fraudes em transações financeiras.

**Arquivos Relacionados:**

- 📓 [Notebook Principal](notebooks/estudos_caso/EstudodeCaso1.ipynb)
- 📊 [Base de Dados](data/databaseFraude.csv)
- 📄 [Documentação](docs/Estudos-de-caso-1-e-2.pdf)

**Principais Resultados:**

- Implementação de 3 modelos: KNN, Árvore de Decisão e Regressão Logística
- Análise comparativa de métricas (acurácia, precisão e recall)
- Identificação das features mais relevantes para detecção de fraudes

### 2. Previsão de Cancelamento de Reservas em Hotéis

> Análise e previsão de cancelamentos de reservas hoteleiras.

**Arquivos Relacionados:**

- 📓 [Notebook Principal](notebooks/estudos_caso/EstudodeCaso2.ipynb)
- 📊 [Base de Dados](data/databaseHotel.csv)
- 📄 [Documentação](docs/Estudos-de-caso-1-e-2.pdf)

### 3. Análise de Preços e COVID-19

> Estudo dividido em duas partes focando em análise imobiliária e impacto da COVID-19.

#### Parte 1: Recomendação de Preços de Aluguel de Apartamentos

- 📓 [Notebook Principal](notebooks/estudos_caso/EstudodeCaso3_Parte1.ipynb)
- 📊 [Base de Dados](data/databaseApartamentos.csv)
- 📄 [Documentação](docs/Estudo-de-caso-3.pdf)

#### Parte 2: Análise de Fatores que Influenciam Óbitos por COVID-19

- 📓 [Notebook Principal](notebooks/estudos_caso/EstudodeCaso3_Parte2.ipynb)
- 📊 [Base de Dados](data/databaseCovid.csv)
- 📄 [Documentação](docs/Estudo-de-caso-3.pdf)

## 📦 Bases de Dados

As bases de dados utilizadas estão disponíveis em:

- [Kaggle](https://www.kaggle.com/datasets)
- [Google Drive - Pasta 1](https://drive.google.com/drive/folders/1HmdzPslXIvonThOhICcPPS6Y-rzojfTJ?usp=sharing)
- [Google Drive - Pasta 2](https://drive.google.com/drive/folders/1HmdzPslXIvonThOhICcPPS6Y-rzojfTJ?usp=sharing)

> **Nota:** Caso não encontre alguma base de dados no Kaggle, consulte as pastas do Google Drive disponibilizadas.

## 🛠️ Tecnologias Utilizadas

- Jupyter Notebook
- Python 3.10 ou superior
- Bibliotecas:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

## 👥 Contribuidores

- João Victor Azevedo dos Santos
- Nathan Maurício Rodrigues Lopes
- Paulo Vinícius Isidro Batista
- Yago Péres dos Santos

## 📝 Mais Informações

Para mais detalhes sobre as bases de dados e suas fontes, consulte o [README da pasta data](data/README.md).
