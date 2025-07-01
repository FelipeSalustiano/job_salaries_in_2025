# 📊 Análise de Salários em Data Science, IA & ML (2025)

Este repositório contém uma análise exploratória de dados sobre salários para cargos nas áreas de Ciência de Dados, Inteligência Artificial e Machine Learning, com foco em dados do ano de 2025. O objetivo do projeto é extrair insights sobre as tendências de remuneração, os modelos de trabalho e como o nível de experiência influencia os salários.

## 🚀 Sobre o Projeto

A análise foi realizada utilizando um notebook Jupyter (`.ipynb`) e a linguagem de programação Python com as bibliotecas Pandas, Matplotlib e Seaborn. O estudo explora um conjunto de dados para responder a perguntas como:

-   Qual a média salarial para diferentes níveis de experiência?
-   Qual a distribuição dos modelos de trabalho (remoto, presencial, híbrido)?

## 📈 Análise e Visualizações

A análise se concentra em dois aspectos principais do mercado de trabalho de dados:

### 1. Média Salarial por Nível de Experiência

Foi observado que a remuneração (em USD) aumenta de forma consistente com o nível de experiência do profissional. Os níveis foram categorizados da seguinte forma:

-   **EN** (Entry-level): Nível de Entrada / Júnior
-   **MI** (Mid-level): Nível Intermediário / Pleno
-   **SE** (Senior-level): Nível Sênior / Especialista
-   **EX** (Executive-level): Nível Executivo / Diretor

### 2. Distribuição do Modelo de Trabalho

A análise da proporção de trabalho remoto, híbrido e presencial revela uma predominância significativa do modelo presencial, seguido pelo remoto.
Este dado mostra como as empresas do setor estão estruturando suas operações em relação ao local de trabalho.

## 🛠️ Limpeza e Tratamento dos Dados

Para garantir uma análise mais precisa, foi realizado um tratamento nos dados para remover *outliers* das colunas de salário (`salary` e `salary_in_usd`). Utilizamos o método de **Intervalo Interquartil (IQR)** para identificar e filtrar valores discrepantes.

## 🗂️ Dataset

O conjunto de dados utilizado, `salaries.csv`, contém 11 colunas, incluindo:

-   `work_year`: O ano em que o salário foi pago.
-   `experience_level`: O nível de experiência no cargo.
-   `employment_type`: O tipo de emprego (ex: tempo integral, meio período).
-   `job_title`: O cargo específico.
-   `salary_in_usd`: O salário anual total, convertido para dólares americanos.
-   `remote_ratio`: A proporção de trabalho remoto (0% para presencial, 50% para híbrido, 100% para remoto).
-   `company_location`: A localização da empresa.
-   `company_size`: O tamanho da empresa (Pequena, Média, Grande).

## 💻 Tecnologias Utilizadas

-   **Linguagem:** Python 3
-   **Bibliotecas:**
    -   Pandas
    -   Matplotlib
    -   Seaborn
-   **Ambiente:** Jupyter Notebook

## 🚀 Como Executar o Projeto

Para reproduzir esta análise em sua máquina local, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
    ```

2.  **Navegue até o diretório do projeto:**
    ```bash
    cd nome-do-repositorio
    ```

3.  **Instale as dependências necessárias:**
    ```bash
    pip install pandas matplotlib seaborn jupyter
    ```

4.  **Inicie o Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

5.  Abra o arquivo `Data_Science,_AI_&_ML_Job_Salaries_in_2025.ipynb` e execute as células.
