# Data Preparation and Outlier Analysis (Etapa 3: Preparação dos Dados e Análise de Outliers)

## Objective / Objetivo

**English:** In this step, we focused on identifying and analyzing outliers in key numerical variables of the dataset. The goal was to determine whether these outliers provide meaningful insights or should be excluded for modeling purposes.

**Português:** Nesta etapa, focamos na identificação e análise de outliers nas principais variáveis numéricas do conjunto de dados. O objetivo foi determinar se esses outliers fornecem insights relevantes ou se devem ser excluídos para fins de modelagem.

---

## Steps Performed / Etapas Realizadas

### 1. Identifying Outliers / Identificando Outliers

**English:**
- Used the Interquartile Range (IQR) method to calculate the lower and upper bounds for outliers.
- Analyzed the variables `ABW` (Average Bunch Weight), `BW` (Bunch Weight), and `Seed Weight` individually to identify extreme values.

**Português:**
- Utilizamos o método do Intervalo Interquartil (IQR) para calcular os limites inferior e superior para os outliers.
- Analisamos as variáveis `ABW` (Peso Médio dos Cachos), `BW` (Peso dos Cachos) e `Seed Weight` (Peso da Semente) individualmente para identificar valores extremos.

### 2. Visualizations / Visualizações

**English:**
- Created boxplots for each variable to visually inspect outliers.
- Compared distributions of outliers and non-outliers to understand their potential impact.

**Português:**
- Criamos boxplots para cada variável para inspecionar visualmente os outliers.
- Comparamos as distribuições de outliers e não-outliers para entender seu impacto potencial.

### 3. Insights and Observations / Insights e Observações

**English:**
- `ABW` and `BW` had no significant outliers under the IQR method.
- `Seed Weight` showed a few outliers. These were analyzed against `Skinfirmness` and `Physiological Maturity` for potential patterns.
- Outliers were retained for further analysis in the modeling phase.

**Português:**
- `ABW` e `BW` não apresentaram outliers significativos pelo método do IQR.
- `Seed Weight` mostrou alguns outliers. Estes foram analisados em relação à `Skinfirmness` e à `Physiological Maturity` para identificar padrões potenciais.
- Os outliers foram mantidos para análises futuras na fase de modelagem.

---

## Tools Used / Ferramentas Utilizadas

**English:**
- Python Libraries: Pandas, Seaborn, Matplotlib.
- Statistical Techniques: Interquartile Range (IQR).

**Português:**
- Bibliotecas Python: Pandas, Seaborn, Matplotlib.
- Técnicas Estatísticas: Intervalo Interquartil (IQR).

---

## Next Steps / Próximos Passos

**English:** Prepare data for modeling by encoding categorical variables and scaling numerical ones. Begin initial model selection.

**Português:** Preparar os dados para modelagem, codificando variáveis categóricas e escalonando variáveis numéricas. Iniciar a seleção inicial de modelos.

---
