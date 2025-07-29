# 📊 Mini Projeto: Data-Driven Insights (Módulo 01)

Este repositório contém o mini projeto de exploração e visualização de dados com Python, desenvolvido como parte do Bootcamp de Engenharia de Dados do Grupo Boticário.

---

## 🎯 Objetivo do Projeto

O principal objetivo foi explorar, transformar e visualizar um conjunto de dados para gerar insights descritivos através do uso de estruturas Python e bibliotecas populares como Pandas, NumPy e Matplotlib.

---

## 📈 Base de Dados Utilizada

Para este projeto, utilizei a base de **Dados de Vendas Simuladas** (`sales_data_sample.csv`), disponível no Kaggle. Essa base contém informações detalhadas sobre transações de vendas, incluindo quantidade, preço, produto, datas e dados de clientes.

---

## 🛠️ Ferramentas e Bibliotecas

* **Linguagem:** Python
* **Ambiente:** Google Colab
* **Bibliotecas:**
    * `pandas`: Para manipulação e análise de dados.
    * `numpy`: Para operações numéricas e com arrays.
    * `matplotlib.pyplot`: Para visualização de dados (gráficos).

---

## ✨ Principais Etapas e Descobertas (Seu Relatório Final)

Neste projeto, explorei a base de dados de vendas simuladas, que contém 2823 linhas e 25 colunas, abrangendo informações detalhadas sobre transações de vendas ao longo de três anos (2003-2005).

* **Exploração Inicial:** Ao realizar a leitura e exploração inicial, observei a dimensão dos dados, as colunas existentes e seus tipos (como `int64`, `float64` e `object`), sendo que algumas colunas de texto (como `ORDERDATE`) precisaram de conversão para tipo de data para análises temporais.

* **Estruturas Python (Listas, Dicionários e Tuplas):** Utilizei estas estruturas para inspecionar rapidamente valores em colunas como `PRODUCTLINE`, `CUSTOMERNAME` e `PRICEEACH`, facilitando uma compreensão inicial de seus conteúdos e relações.

* **Lógica Condicional e Laços:** Apliquei `if/elif/else` para classificar preços e laços `for`/`while` para operar sobre sequências de dados, como somar os primeiros preços, demonstrando a capacidade de automação e extração de informações específicas.

* **Novas Métricas de Negócio:** Através de operações com Pandas, foram criadas métricas importantes como o `LUCRO_ESTIMADO` (assumindo 30% de margem sobre as vendas) e a `DIF_MSRP_PRICE` (diferença entre o preço sugerido e o preço real de venda). Essas novas colunas permitiram uma compreensão mais aprofundada da rentabilidade e das estratégias de precificação.

* **Análise Numérica com NumPy:** O uso de arrays NumPy otimizou operações em massa e cálculos agregados sobre volumes de vendas (soma total e média), permitindo uma visão geral do desempenho das vendas de forma eficiente.

* **Filtragem e Agrupamento com Pandas:** Operações de seleção, filtragem (ex: vendas acima de 5000) e agrupamento por `PRODUCTLINE` com Pandas revelaram as linhas de produto que mais contribuem para a receita total (como "Motorcycles", "Classic Cars" e "Vintage Cars"), sendo cruciais para entender o desempenho das categorias e focar estratégias.

* **Visualização de Dados:** Os gráficos gerados com Matplotlib foram essenciais para transformar dados complexos em insights visuais. O **Gráfico de Barras** destacou as linhas de produto de maior receita. O **Gráfico de Dispersão** ilustrou a relação entre preço unitário e quantidade pedida. O **Gráfico de Linha** mostrou a tendência de vendas por ano, revelando o pico em 2004 e a aparente incompletude dos dados de 2005.

### Conclusão:

Este projeto me permitiu uma imersão prática na exploração e transformação de dados utilizando Python, evidenciando como Pandas e NumPy são ferramentas poderosas para manipular e agregar informações. As visualizações com Matplotlib foram essenciais para transformar dados complexos em insights acionáveis, destacando a importância de linhas de produto específicas e a dinâmica de preços nas vendas. As descobertas apontam para oportunidades de aprofundar a análise em categorias de maior receita e investigar a completude dos dados anuais para uma previsão mais precisa.

---

## 👨‍💻 Como Rodar o Projeto

1.  Clone este repositório para o seu ambiente local.
2.  Abra o arquivo `data_driven_insights.ipynb` no Google Colab.
3.  Certifique-se de ter o arquivo `sales_data_sample.csv` na pasta `data-driven-insights` do seu Google Drive e monte-o no Colab.
4.  Execute as células do notebook sequencialmente.

---

## 🙋 Contato

Bruno Brasileiro - [brunobrasileiro85@gmail.com](mailto:brunonexus85@gmail.com)
