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

### **Step 1: Data Loading and EDA**

**English:**
1. Imported the dataset (`Analysis.csv`) into Python.
2. Examined the structure and characteristics of the data:
   - Checked data types and column names.
   - Identified missing or inconsistent values.
3. Generated descriptive statistics to understand distributions.
4. Created visualizations:
   - Histograms to analyze the distribution of numerical variables.
   - Scatter plots to explore relationships between key variables.

**Português:**
1. Importou-se o conjunto de dados (`Analysis.csv`) no Python.
2. Examinou-se a estrutura e as características dos dados:
   - Verificação dos tipos de dados e nomes das colunas.
   - Identificação de valores ausentes ou inconsistentes.
3. Geração de estatísticas descritivas para entender distribuições.
4. Criação de visualizações:
   - Histogramas para analisar a distribuição de variáveis numéricas.
   - Gráficos de dispersão para explorar relações entre variáveis-chave.

### **Step 2: Correlation Analysis**

**English:**
1. Generated a correlation matrix to identify variable relationships.
2. Visualized pairs of variables with high or moderate correlations:
   - Strong positive correlation (~0.88) between `Skinfirmness` and `PhysiologicalMaturity`.
   - Moderate positive correlation (~0.65) between `BL` (Bunch Length) and `BW` (Bunch Weight).
   - Weak positive correlation (~0.12) between `Seed weight` and `PhysiologicalMaturity`.
3. Interpreted the results and documented the insights.

**Português:**
1. Geração de uma matriz de correlação para identificar relações entre variáveis.
2. Visualização de pares de variáveis com correlações altas ou moderadas:
   - Correlação positiva forte (~0.88) entre `Skinfirmness` e `PhysiologicalMaturity`.
   - Correlação positiva moderada (~0.65) entre `BL` (Comprimento do Cacho) e `BW` (Peso do Cacho).
   - Correlação positiva fraca (~0.12) entre `Seed weight` e `PhysiologicalMaturity`.
3. Interpretação dos resultados e documentação dos insights.

### **Step 3: Outlier Analysis**

**English:**

1. Identified outliers in key variables (ABW, BW, Seed Weight) using the Interquartile Range (IQR) method.
2. Visualized boxplots for each variable to highlight outliers.
3. Compared the characteristics of outliers with non-outliers to identify patterns.
4. Retained all data, including outliers, for potential modeling and analysis in the next steps.

**Português:**
1. Identificou-se outliers nas variáveis principais (ABW, BW, Seed Weight) utilizando o método do Intervalo Interquartil (IQR).
2. Visualização de boxplots para cada variável destacando os outliers.
3. Comparação das características dos outliers com os não-outliers para identificar padrões.
4. Mantiveram-se todos os dados, incluindo os outliers, para modelagem e análises futuras.

### **Step 4: Data Modeling and Feature Importance**

**English:**
1. Prepared data for machine learning models by normalizing numerical variables and encoding categorical variables.
2. Trained several models, including Random Forest and Gradient Boosting, with hyperparameter tuning using GridSearchCV.
3. Evaluated model performance using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score.
4. Visualized feature importance to understand the most influential variables in predicting the target variable (`Skinfirmness`).

**Português:**
1. Preparou-se os dados para modelos de aprendizado de máquina, normalizando variáveis numéricas e codificando variáveis categóricas.
2. Treinamento de diversos modelos, incluindo Random Forest e Gradient Boosting, com ajuste de hiperparâmetros utilizando GridSearchCV.
3. Avaliação do desempenho dos modelos utilizando Erro Quadrático Médio (MSE), Erro Absoluto Médio (MAE) e Coeficiente de Determinação (R²).
4. Visualização da importância das variáveis para entender quais são mais influentes na predição da variável alvo (`Skinfirmness`).

---

## Tools Used / Ferramentas Utilizadas

**English:**
- **Programming Language:** Python.
- **Libraries:** Pandas, Matplotlib, Seaborn, Scikit-learn.
- **Environment:** Google Colab.

**Português:**
- **Linguagem de Programação:** Python.
- **Bibliotecas:** Pandas, Matplotlib, Seaborn, Scikit-learn.
- **Ambiente:** Google Colab.

---

## Next Steps / Próximos Passos

**English:**
- Integrate model insights into Power BI dashboards.
- Present findings interactively and explore relationships visually.

**Português:**
- Integrar os insights do modelo em dashboards no Power BI.
- Apresentar as descobertas de forma interativa e explorar relações visualmente.

---

## Repository Structure / Estrutura do Repositório

```
|-- data/
|   |-- Analysis.csv          # Conjunto de dados original
|
|-- docs/
|   |-- step1_data_loading_and_eda.md   # Etapa 1
|   |-- step2_correlation_analysis.md   # Etapa 2
|   |-- step3_outlier_analysis.md       # Etapa 3
|   |-- step4_data_modeling.md          # Etapa 4
|
|-- notebooks/
|   |-- Wine_Genotype_Classification - Etapa 1.ipynb   # Notebook da Etapa 1
|   |-- Wine_Genotype_Classification_Etapa_2.ipynb   # Notebook da Etapa 2
|   |-- Wine_Genotype_Classification_Etapa_3.ipynb   # Notebook da Etapa 3
|   |-- Wine_Genotype_Classification_Etapa_4.ipynb   # Notebook da Etapa 4
|
|-- README.md                 # Descrição geral do projeto

```
