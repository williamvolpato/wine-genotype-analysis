# Step 4: Model Evaluation and Feature Importance Analysis

## Objective / Objetivo

**English:**
The objective of this step is to evaluate the optimized machine learning model's performance and identify the most important variables that influence the target variable (`Skinfirmness`).

**Português:**
O objetivo desta etapa é avaliar o desempenho do modelo de aprendizado de máquina otimizado e identificar as variáveis mais importantes que influenciam a variável alvo (`Skinfirmness`).

---

## Tasks Performed / Tarefas Realizadas

### **Model Optimization and Evaluation / Otimização e Avaliação do Modelo**

**English:**
1. Implemented and optimized the Gradient Boosting model using GridSearchCV to fine-tune hyperparameters:
   - Best hyperparameters identified: `learning_rate=0.01`, `max_depth=3`, `min_samples_leaf=5`, `min_samples_split=2`, `n_estimators=100`.
2. Evaluated the model's performance on the test dataset:
   - Metrics:
     - **Mean Squared Error (MSE):** 36.09
     - **Mean Absolute Error (MAE):** 5.03
     - **R² Score:** 0.30
3. Visualized real vs. predicted values and residual distribution.

**Português:**
1. Implementou-se e otimizou-se o modelo Gradient Boosting utilizando o GridSearchCV para ajustar hiperparâmetros:
   - Melhores hiperparâmetros identificados: `learning_rate=0.01`, `max_depth=3`, `min_samples_leaf=5`, `min_samples_split=2`, `n_estimators=100`.
2. Avaliou-se o desempenho do modelo no conjunto de dados de teste:
   - Métricas:
     - **Erro Quadrático Médio (MSE):** 36.09
     - **Erro Absoluto Médio (MAE):** 5.03
     - **R² Score:** 0.30
3. Visualizou-se os valores reais vs. previstos e a distribuição dos resíduos.

---

### **Feature Importance Analysis / Análise de Importância das Variáveis**

**English:**
1. Extracted feature importance values from the optimized Gradient Boosting model.
2. Visualized the top 10 most important features influencing `Skinfirmness`:
   - Top features:
     - `pedunclelength`
     - `PhysiologicalMaturity`
     - `Seed weight`
     - `TSS`
     - `Bunlen`
     - ...
3. Generated a horizontal bar chart for visual analysis.

**Português:**
1. Extraiu-se os valores de importância das variáveis do modelo Gradient Boosting otimizado.
2. Visualizou-se as 10 variáveis mais importantes que influenciam `Skinfirmness`:
   - Principais variáveis:
     - `pedunclelength`
     - `PhysiologicalMaturity`
     - `Seed weight`
     - `TSS`
     - `Bunlen`
     - ...
3. Gerou-se um gráfico de barras horizontal para análise visual.

---

## Key Insights / Principais Insights

**English:**
- The feature `pedunclelength` has the highest importance, followed by `PhysiologicalMaturity` and `Seed weight`, indicating their strong influence on `Skinfirmness`.
- The optimized model demonstrates improved performance compared to earlier iterations, but there is room for further refinement.

**Português:**
- A variável `pedunclelength` apresenta a maior importância, seguida de `PhysiologicalMaturity` e `Seed weight`, indicando sua forte influência sobre `Skinfirmness`.
- O modelo otimizado demonstra desempenho melhorado em relação às iterações anteriores, mas há espaço para refinar ainda mais.

---

## Next Steps / Próximos Passos

**English:**
- Integrate machine learning results with Power BI to create interactive dashboards.
- Explore additional feature engineering techniques to further improve model performance.

**Português:**
- Integrar os resultados do aprendizado de máquina ao Power BI para criar dashboards interativos.
- Explorar técnicas adicionais de engenharia de variáveis para melhorar ainda mais o desempenho do modelo.
