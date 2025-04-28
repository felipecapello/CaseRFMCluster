# 📊 Clustering de Clientes — Caso de Estudo de E-commerce

## Descrição

Este projeto realiza a **clusterização de clientes** de um e-commerce britânico utilizando a metodologia **RFM** (Recency, Frequency, Monetary) para segmentação de clientes.  
O objetivo é agrupar os clientes em diferentes perfis de comportamento, auxiliando na definição de **estratégias de fidelização** e marketing.

O notebook foi desenvolvido como um case prático para alunos da **DNC**.

## 🔍 Metodologia

As etapas principais do projeto incluem:

1. **Entendimento do Problema (Business Understanding)**
   - Definição do desafio de negócios: segmentar clientes com base em comportamentos de compra.

2. **Entendimento dos Dados (Data Understanding)**
   - Análise exploratória dos dados transacionais entre dezembro de 2010 e dezembro de 2011.
   - Fonte dos dados: [Ecommerce Data - Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data).

3. **Preparação dos Dados**
   - Cálculo das métricas **RFM** para cada cliente.
   - Tratamento de outliers e dados inconsistentes.

4. **Modelagem**
   - Aplicação de algoritmos de clusterização:
     - K-Means
     - Gaussian Mixture
     - DBSCAN
     - MeanShift
     - Agglomerative Clustering
   - Escalonamento dos dados usando `StandardScaler`.

5. **Avaliação**
   - Uso de métricas como **Silhouette Score**, **Davies-Bouldin Score** e **Calinski-Harabasz Score** para avaliar a qualidade dos agrupamentos.

6. **Visualizações**
   - Gráficos de dispersão, dendrogramas e visualizações de cotovelos para análise dos clusters.

## 📦 Dependências

Certifique-se de ter as seguintes bibliotecas Python instaladas:

```bash
pip install pandas numpy seaborn matplotlib plotly sidetable scikit-learn scipy yellowbrick
