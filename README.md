# README - Wine Genotype Analysis

## Objective / Objetivo

**English:**
This project aims to explore and analyze a dataset of wine genotypes to uncover patterns, relationships, and insights that can assist in decision-making. The data includes various characteristics of grape genotypes, such as firmness, maturity, and weight, which are analyzed for trends and correlations.

**Português:**
Este projeto tem como objetivo explorar e analisar um conjunto de dados de genótipos de vinho para descobrir padrões, relações e insights que possam auxiliar na tomada de decisões. Os dados incluem diversas características dos genótipos de uva, como firmeza, maturidade e peso, que são analisadas em busca de tendências e correlações.

---

## Dataset Description / Descrição do Conjunto de Dados

**English:**
- **Source:** Kaggle - Wine Genotype Classification Dataset.
- **Structure:** The dataset contains numerical and categorical variables describing grape genotypes.
- **Key variables:**
  - `Genotypes`: Grape genotype names.
  - `Skinfirmness`: Firmness of the grape skin.
  - `PhysiologicalMaturity`: Maturity level of the grapes.
  - `ABW`, `BW`: Average and total bunch weights.

**Português:**
- **Fonte:** Kaggle - Conjunto de Dados de Classificação de Genótipos de Vinho.
- **Estrutura:** O conjunto de dados contém variáveis numéricas e categóricas que descrevem os genótipos de uva.
- **Variáveis principais:**
  - `Genotypes`: Nomes dos genótipos de uva.
  - `Skinfirmness`: Firmeza da pele da uva.
  - `PhysiologicalMaturity`: Nível de maturidade fisiológica das uvas.
  - `ABW`, `BW`: Pesos médio e total dos cachos.

---

## Steps Performed / Etapas Realizadas

**English:**
1. **Data Loading:** The dataset was imported into Python for analysis.
2. **Exploratory Data Analysis (EDA):**
   - Visualized data structure, statistics, and distributions.
   - Identified relationships and correlations between variables.
3. **Key Findings:**
   - Strong correlation (~0.88) between `Skinfirmness` and `PhysiologicalMaturity`.
   - Boxplots showed variability in `ABW` (Average Bunch Weight) across different genotypes.

**Português:**
1. **Carregamento dos Dados:** O conjunto de dados foi importado para Python para análise.
2. **Análise Exploratória de Dados (EDA):**
   - Visualização da estrutura dos dados, estatísticas e distribuições.
   - Identificação de relações e correlações entre variáveis.
3. **Principais Descobertas:**
   - Correlação forte (~0.88) entre `Skinfirmness` e `PhysiologicalMaturity`.
   - Boxplots mostraram variabilidade em `ABW` (Peso Médio dos Cachos) entre diferentes genótipos.

---

## Tools Used / Ferramentas Utilizadas

**English:**
- **Programming Language:** Python.
- **Libraries:** Pandas, Matplotlib, Seaborn.
- **Environment:** Google Colab.

**Português:**
- **Linguagem de Programação:** Python.
- **Bibliotecas:** Pandas, Matplotlib, Seaborn.
- **Ambiente:** Google Colab.

---

## Next Steps / Próximos Passos

**English:**
- Develop dashboards in Power BI to present insights interactively.
- Explore the impact of genotypes on other key variables.

**Português:**
- Desenvolver dashboards no Power BI para apresentar insights de forma interativa.
- Explorar o impacto dos genótipos em outras variáveis principais.

---

## Repository Structure / Estrutura do Repositório

```
|-- data/
    |-- Analysis.csv  # Raw dataset
|-- notebooks/
    |-- wine_genotype_analysis.ipynb  # Notebook with analysis
|-- README.md  # Project description
```

