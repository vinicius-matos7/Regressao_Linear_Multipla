# Análise Preditiva de Preços de Imóveis com Regressão Linear Múltipla

![Status](https://img.shields.io/badge/Status-Finalizado-green)

Este repositório documenta um projeto de Machine Learning que aplica o algoritmo de **Regressão Linear Múltipla**. O objetivo é construir um modelo preditivo robusto, utilizando diversas variáveis independentes para estimar o valor de uma variável dependente.

## 🎯 Objetivo

O projeto visa prever o preço de imóveis com base em um conjunto de características, como a taxa de criminalidade da região, o número médio de quartos, a idade do imóvel, entre outros.

Diferente da Regressão Linear Simples, que utiliza apenas uma variável para fazer a previsão, o modelo múltiplo permite uma análise muito mais rica e precisa, pois considera o impacto combinado de vários fatores no resultado final.

## 🧠 Conceitos Abordados

Neste projeto, foram explorados conceitos fundamentais de qualquer fluxo de trabalho de Machine Learning, incluindo:

- **Análise Exploratória de Dados (EDA):** Entendimento inicial dos dados e das relações entre as variáveis.
- **Pré-processamento de Dados:** Tratamento de valores ausentes e normalização de features.
- **Análise de Correlação:** Utilização de mapas de calor (heatmaps) para identificar as variáveis mais correlacionadas com o preço dos imóveis e evitar multicolinearidade.
- **Separação de Dados (Train/Test Split):** Divisão do dataset em conjuntos de treino e teste para validar a performance do modelo de forma imparcial.
- **Treinamento do Modelo:** Utilização da classe `LinearRegression` do Scikit-learn.
- **Avaliação de Métricas:** Análise de métricas como o **Coeficiente de Determinação (R²)** e o **Erro Quadrático Médio (MSE)** para avaliar a acurácia do modelo.

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Bibliotecas:**
  - **Pandas:** Para manipulação e leitura dos dados.
  - **NumPy:** Para operações numéricas.
  - **Scikit-learn:** Para a criação do modelo e avaliação das métricas.
  - **Matplotlib & Seaborn:** Para a visualização dos dados e dos resultados.

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/vinicius-matos7/Regressao_Linear_Multipla.git](https://github.com/vinicius-matos7/Regressao_Linear_Multipla.git)
