# Trabalho Final da Unidade 03 – Análise de Dados em Python

## Descrição do Projeto

Este projeto consiste em uma análise detalhada dos dados de vendas da empresa, abrangendo o período de 2017 a 2020. Os dados foram fornecidos em arquivos CSV e Excel, contendo informações completas sobre as vendas realizadas, permitindo uma avaliação profunda do desempenho comercial.

---

## Objetivos

Como analista de dados, o objetivo é responder aos seguintes pontos:

1. Realizar toda a **Análise Exploratória dos Dados (EDA)**.
2. Criar conexão com banco de dados **PostgreSQL** e armazenar os dados.
3. Calcular a **quantidade vendida por ano** e plotar gráfico correspondente.
4. Calcular o **total de vendas por ano** e plotar gráfico de barras com valores em reais (R$).
5. Determinar a quantidade de vendas e o total de vendas para cada categoria.
6. Identificar a categoria que teve a **menor e maior quantidade vendida** e suas respectivas quantidades.
7. Analisar o valor de venda e a quantidade vendida anual para a categoria com maior quantidade vendida.
8. Descobrir qual o **modelo e cor de bicicleta mais vendidos**.
9. Identificar a subcategoria que tem maior quantidade vendida para cada categoria.
10. Calcular o **total de vendas por estado** e suas participações percentuais (com valores em 2 casas decimais).
11. Apresentar o total de vendas das **Top 5 cidades** e a que estado cada cidade pertence.
12. Calcular o total de vendas por região e suas participações, apresentando um gráfico de pizza com os valores em R$ e porcentagens.
13. Analisar o total de vendas por ano para cada categoria, criando um pivot com linhas para regiões e colunas para anos, e plotar gráfico de barras agrupadas (clusterizado).
14. Analisar o total de vendas por ano para cada região, criando um pivot similar e plotar gráfico de linha para mostrar a tendência anual.
15. Visualizar a distribuição da quantidade vendida e do total de vendas para cada categoria, utilizando um gráfico combinado onde as barras representam o valor total de vendas e a linha a quantidade vendida. Em seguida, exportar os dados e gráficos para Excel e enviar por e-mail.

---

## Estrutura dos Dados

- **Arquivos CSV**: Contêm os dados de vendas por ano (2017, 2018, 2019 e 2020).
- **Arquivos Excel**: Contêm informações complementares sobre cidades, estados, regiões, categorias, subcategorias e modelos de bicicletas.

---

## Tecnologias Utilizadas

- Python 3.x
- Bibliotecas:
  - `pandas` para manipulação e análise de dados
  - `matplotlib` e `seaborn` para visualização gráfica
  - `openpyxl` para exportação para Excel
  - `sqlalchemy` e `psycopg2` para conexão e armazenamento no banco PostgreSQL
- Banco de dados PostgreSQL
- Jupyter Notebook para desenvolvimento e documentação interativa

---

## Como Executar o Projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/PereiraTalles/Analise_Python.git
   cd Analise_Python
