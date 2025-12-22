# 🏠 Predição de Preço de Imóveis com Regressão Linear Múltipla
## 📌 Visão Geral

Este projeto foi desenvolvido como desafio final de uma oficina introdutória de Machine Learning e Ciência de Dados, com foco em aplicar, na prática, todo o fluxo de um projeto de dados — da exploração ao treinamento e avaliação de modelos.

O objetivo principal foi prever o preço de imóveis a partir de variáveis estruturais e locacionais, utilizando Regressão Linear Múltipla.

## 🎯 Objetivo do Projeto

Construir um modelo preditivo capaz de estimar o preço de imóveis (R$ mil) com base em características como:

Área do imóvel

Idade

Distância até o centro

Número de garagens

Vista para o mar

Total de cômodos

Além da predição, o projeto buscou entender o impacto de cada variável, validar os pressupostos do modelo linear e interpretar os resultados de forma crítica.

## 🔍 Etapas do Projeto
1️⃣ Exploração e Análise dos Dados

Identificação de dados ausentes

Análise de distribuições

Detecção de outliers

Análise de correlação entre variáveis

2️⃣ Pré-processamento

Tratamento de valores ausentes (mediana, média ou moda, conforme o tipo da variável)

Conversão de variáveis categóricas em numéricas

Remoção de variáveis redundantes

Análise de multicolinearidade utilizando VIF (Variance Inflation Factor)

3️⃣ Modelagem

Regressão Linear Múltipla com Scikit-learn

Separação dos dados em treino e teste

Interpretação dos coeficientes do modelo

4️⃣ Avaliação

Métricas utilizadas:

R²

RMSE

MAE

Análise gráfica:

Predito vs Real

Distribuição dos resíduos

Q-Q Plot dos resíduos

📊 Resultados

O modelo apresentou bom desempenho e boa capacidade de generalização, explicando aproximadamente 77% da variância dos preços dos imóveis.

A análise dos resíduos indicou:

Distribuição aproximadamente normal

Erros centrados em zero

Ausência de viés sistemático relevante

Esses resultados mostram que a Regressão Linear Múltipla é adequada para o problema proposto, considerando as variáveis disponíveis.
