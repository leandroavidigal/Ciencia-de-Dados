# 📊 **Regressão Linear e Logística - Modelagem e Análise Preditiva**

A **regressão linear e logística** são técnicas estatísticas fundamentais para modelagem e previsão em diversas áreas, desde análise econômica até diagnósticos médicos. Este repositório reúne projetos práticos aplicando essas metodologias a diferentes contextos, como **previsão de renda, análise de gorjetas e diagnóstico de doenças cardíacas**.  

Cada estudo busca aprimorar a compreensão dos dados e melhorar a precisão dos modelos através de transformações matemáticas, seleção de variáveis e técnicas de regularização.

---

## 📌 **Projetos**

### **1️⃣ Análise de Gorjetas e Modelos de Regressão**

#### **Objetivo**
Explorar a relação entre **valor da conta** e **gorjeta deixada pelos clientes**, utilizando a base de dados **tips** do Seaborn. O foco está na comparação entre a previsão do **valor absoluto** da gorjeta e sua **proporção em relação à conta líquida**.

#### **Principais Análises**
✔️ Construção de modelos de regressão linear para prever o valor da gorjeta.  
✔️ Comparação entre regressão do valor absoluto da gorjeta (**tip ~ net_bill**) e percentual da gorjeta (**tip_pct ~ net_bill**).  
✔️ Avaliação da qualidade do ajuste através do coeficiente de determinação (**R²**).  
✔️ Interpretação dos coeficientes para entender o impacto de variáveis como **gênero, fumo e dia da semana**.  

---

### **2️⃣ Aprimoramento do Ajuste no Percentual de Gorjetas**

#### **Objetivo**
Aprofundar a análise sobre a relação entre **percentual de gorjeta (tip_pct)** e **valor da conta líquida (net_bill)**, aplicando transformações matemáticas para melhorar o ajuste da regressão.

#### **Principais Análises**
✔️ Comparação entre **modelos lineares simples e transformados**.  
✔️ Aplicação de **transformações logarítmicas e polinomiais** para capturar padrões não lineares nos dados.  
✔️ Análise de resíduos para avaliar a qualidade dos modelos ajustados.  
✔️ Comparação dos modelos através do coeficiente de determinação (**R²**) e seleção do melhor ajuste.

---

### **3️⃣ Análise de Regressão Aplicada ao Valor da Gorjeta e Previsão de Renda**

#### **Objetivo**
Explorar a **regressão linear múltipla** em dois contextos distintos:
**Análise da gorjeta**: Avaliar como fatores como **gênero, hábito de fumar e valor da conta** influenciam a gorjeta deixada.  
**Predição de renda**: Modelar a **renda** com base em características individuais, como **idade, escolaridade e tempo de emprego**.

#### **Principais Análises**
✔️ Construção de **modelos de regressão múltipla** para prever tanto gorjetas quanto renda.  
✔️ Uso de **transformações polinomiais e logarítmicas** para capturar relações não lineares.  
✔️ Avaliação dos modelos utilizando **R²** e análise de resíduos.  
✔️ Interpretação dos coeficientes para compreender o impacto de variáveis independentes.

---

### **4️⃣ Regressão Múltipla Aplicada à Previsão de Renda**

#### **Objetivo**
Avaliar **diferentes técnicas de modelagem** para prever **renda**, comparando regressão múltipla, regularização **Ridge e LASSO**, seleção de variáveis **stepwise** e **árvores de regressão**.

#### **Principais Análises**
✔️ Construção de modelos de **Regressão Linear Múltipla** para prever a renda com base em características socioeconômicas.  
✔️ Implementação de **regularização Ridge e LASSO** para evitar overfitting e melhorar a generalização do modelo.  
✔️ Aplicação da técnica **stepwise** para seleção automática de variáveis mais relevantes.  
✔️ Comparação do desempenho dos modelos utilizando **coeficiente de determinação (R²) e erro quadrático médio (MSE)**.  
✔️ Exploração de técnicas para aprimorar a modelagem, incluindo **transformações matemáticas e combinações de variáveis**.

---

### **5️⃣ Regressão Múltipla para Previsão de Renda**

#### **Objetivo**
Aplicar **Regressão Linear Múltipla** para modelar a **renda**, explorando fatores individuais e socioeconômicos que influenciam o rendimento das pessoas.

#### **🔍 Principais Análises**
✔️ Construção de um **modelo estatístico robusto e interpretável**.  
✔️ Utilização da base de dados **previsao_de_renda.csv** para análise.  
✔️ Exploração do impacto de variáveis explicativas no **logaritmo da renda**.  
✔️ Avaliação da qualidade do modelo utilizando **Statsmodels e Patsy**.

---

### **6️⃣ Regressão Logística: Análise de Doença Cardíaca**

#### **Objetivo**
Utilizar **Regressão Logística** para prever a **presença de doença cardíaca**, utilizando variáveis clínicas e exames médicos.

#### **Principais Análises**
✔️ Análise exploratória da base **Heart Disease Data Set (UCI Machine Learning Repository)**.  
✔️ Construção de tabelas estatísticas para entender a influência de diferentes variáveis no risco de doença cardíaca.  
✔️ Cálculo de **probabilidades, odds e Weight of Evidence (WOE)** para medir a relevância das variáveis.  
✔️ Ajuste de um **modelo de regressão logística** e interpretação dos coeficientes.  
✔️ Avaliação da calibração e discriminação do modelo preditivo.  

---

### **7️⃣ Regressão Logística: Modelagem e Avaliação da Doença Cardíaca**

#### **Objetivo**
Aprofundar a **modelagem da regressão logística**, refinando a seleção de variáveis e aprimorando a avaliação do modelo preditivo para **diagnóstico de doença cardíaca**.

#### **Principais Análises**
✔️ **Automatização** da análise bivariada para variáveis qualitativas e quantitativas.  
✔️ **Ajuste de modelos de regressão logística**, interpretando seus parâmetros e coeficientes.  
✔️ **Avaliação da calibragem** e discriminação do modelo utilizando métricas estatísticas, como **AUC, GINI e KS**.  
✔️ **Refinamento do modelo**, removendo e inserindo variáveis para aprimorar o desempenho preditivo.  
✔️ Comparação entre diferentes abordagens, selecionando a melhor configuração para previsão da doença cardíaca.

---

## 🚀 **Tecnologias Utilizadas**

- **Python**   
- **Pandas** para manipulação e estruturação dos dados.  
- **Seaborn e Matplotlib** para visualização de dados.  
- **Statsmodels e Patsy** para modelagem estatística.  
- **Scikit-learn** para validação e métricas de desempenho.  
