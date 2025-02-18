# 📊 Regressão Linear e Logística

A **regressão linear e logística** são técnicas estatísticas essenciais para modelagem e previsão em diversas áreas. Este repositório reúne projetos práticos aplicando essas metodologias a diferentes contextos: gorjetas em restaurantes e predição de renda. Cada análise busca aprimorar a compreensão dos dados e melhorar a precisão dos modelos através de transformações e ajustes adequados.

---

## 📌 Projetos

### 1. Análise de Gorjetas e Modelos de Regressão

#### **Objetivo**
Explorar a relação entre o valor da conta e a gorjeta oferecida pelos clientes usando a base de dados **tips** do Seaborn. O foco está na comparação entre a previsão do valor absoluto da gorjeta e sua proporção em relação à conta líquida.

#### **Principais Análises**
✔️ Modelagem da relação entre o valor gasto e a gorjeta deixada.  
✔️ Comparação entre regressão do valor absoluto da gorjeta (**tip ~ net_bill**) e percentual da gorjeta (**tip_pct ~ net_bill**).  
✔️ Avaliação do coeficiente de determinação (**R²**) para medir a qualidade dos ajustes.

---

### 2. Aprimoramento do Ajuste no Percentual de Gorjetas

#### **Objetivo**
Aprofundar a análise sobre a relação entre **percentual de gorjeta (tip_pct)** e **valor da conta líquida (net_bill)**, aplicando transformações matemáticas para melhorar o ajuste da regressão.

#### **Principais Análises**
✔️ Comparação de modelos lineares simples e transformados.  
✔️ Aplicação de **transformações logarítmicas e polinomiais** para ajustar a não linearidade da relação.  
✔️ Análise dos resíduos para avaliar a qualidade do modelo.  
✔️ Comparação dos modelos através do coeficiente de determinação (**R²**).  

---

### 3. Análise de Regressão Aplicada ao Valor da Gorjeta e Previsão de Renda

#### **Objetivo**
Aplicar a regressão linear em dois contextos distintos:
**Análise da gorjeta**: Avaliar como fatores como gênero, hábito de fumar e valor da conta influenciam a gorjeta deixada.  
**Predição de renda**: Modelar a renda com base em características individuais como idade e tempo de emprego.

#### **Principais Análises**
✔️ Construção de modelos de regressão múltipla para ambas as aplicações.  
✔️ Uso de **transformações polinomiais e logarítmicas** para capturar relações não lineares.  
✔️ Avaliação dos modelos usando **R²** e análise de resíduos.  
✔️ Interpretação dos coeficientes para compreender o impacto das variáveis independentes.

---

## 🚀 Tecnologias Utilizadas

- **Python**
- **Pandas** para manipulação e estruturação dos dados.
- **Seaborn** para visualização exploratória dos dados.
- **Statsmodels e Patsy** para modelagem estatística.
- **Scikit-learn** para validação e métricas de desempenho.
