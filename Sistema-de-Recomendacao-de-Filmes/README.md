## Sistema de Recomendação de Filmes com Machine Learning - Análise do MovieLens

Este projeto implementa e avalia **diferentes modelos de recomendação de filmes** utilizando dados reais do **dataset MovieLens**. O objetivo é identificar padrões de comportamento dos usuários e gerar recomendações personalizadas utilizando técnicas de **Machine Learning**, como **Filtragem Colaborativa, Fatoração de Matrizes (SVD) e Modelos Aleatórios**.

---

## **Objetivos do Projeto**
✔️ **Analisar o comportamento dos usuários** com base no dataset MovieLens.  
✔️ **Implementar diferentes modelos de recomendação**, como:
   - Filtragem Colaborativa baseada em Usuários (User-User)
   - Filtragem Colaborativa baseada em Itens (Item-Item)
   - Fatoração de Matrizes (SVD)
   - Modelo Aleatório (Baseline)  
✔️ **Comparar o desempenho dos modelos** utilizando métricas como **RMSE, Precisão e Recall**.  
✔️ **Demonstrar como esses sistemas podem ser aplicados** em diferentes domínios, como **streaming, e-commerce e educação**.  

---

## **Modelos Utilizados**
1️⃣ **Modelo Aleatório (NormalPredictor)**  
   - Recomenda filmes de forma **aleatória**, servindo apenas como **baseline**.  
   - **RMSE:** 1.5218 → **Pior desempenho** entre os modelos testados.  

2️⃣ **Filtragem Colaborativa Baseada em Usuários (KNNBasic - user-user)**  
   - Usa **similaridade entre usuários** para recomendar filmes.  
   - **RMSE:** 0.9785 → Desempenho significativamente melhor que o modelo aleatório.  

3️⃣ **Filtragem Colaborativa Baseada em Itens (KNNBasic - item-item)**  
   - Baseia-se na **similaridade entre filmes** para fazer recomendações.  
   - **RMSE:** 0.9738 → Desempenho ligeiramente superior ao modelo usuário-usuário.  

4️⃣ **Fatoração de Matrizes (SVD - Singular Value Decomposition)**  
   - Utiliza **aprendizado latente** para capturar padrões complexos.  
   - **RMSE:** 0.9346 → **Melhor modelo**, fornecendo recomendações mais personalizadas.  

---

## **Resultados - Comparação entre Modelos**
| Modelo | RMSE (Erro Médio Quadrático) | Melhor Aplicação |
|--------|----------------------------|----------------|
| **NormalPredictor** (Aleatório) | **1.5218** | Nenhuma (apenas baseline) |
| **KNN (Usuário-Usuário)** | **0.9785** | Indicação baseada em usuários similares |
| **KNN (Item-Item)** | **0.9738** | Indicação baseada na similaridade entre filmes |
| **SVD (Fatoração de Matrizes)** | **0.9346** | Melhor para recomendações personalizadas |

**Conclusão:**  
✔️ O modelo **SVD apresentou o melhor desempenho**, sendo mais eficiente para capturar padrões ocultos.  
✔️ A **Filtragem Colaborativa** (usuário-usuário e item-item) teve um **desempenho sólido**, mostrando-se útil para recomendações.  
✔️ O **Modelo Aleatório** teve o pior desempenho, servindo apenas como um **baseline**.  

---

## **Precisão e Recall @k**
Além do RMSE, avaliamos a precisão e recall para **k=5 e k=10**, analisando a capacidade dos modelos de recomendar filmes relevantes.

| Modelo | Precisão @5 | Recall @5 | Precisão @10 | Recall @10 |
|--------|------------|-----------|-------------|------------|
| **NormalPredictor** | 0.584 | 0.339 | 0.587 | 0.437 |
| **KNN (Item-Item)** | 0.817 | 0.390 | 0.789 | 0.534 |
| **SVD (Fatoração de Matrizes)** | 0.782 | 0.428 | 0.761 | 0.569 |

**Observações**:  
✔️ **KNN (item-item) apresentou maior precisão**, indicando que recomenda itens muito relevantes.  
✔️ **SVD teve um melhor equilíbrio entre precisão e recall**, tornando-se a opção mais robusta.  
✔️ O modelo aleatório (**NormalPredictor**) teve o pior desempenho.  

---

## **Aplicações no Mundo Real**
Os modelos explorados neste projeto podem ser aplicados em diversas áreas:

✔️ **📽Streaming (Netflix, Prime Video, Disney+)** → Recomendação de filmes e séries.  
✔️ **E-commerce (Amazon, Shopee, Mercado Livre)** → Sugestão de produtos baseados no histórico do usuário.  
✔️ **Educação (Coursera, Udemy, Alura)** → Recomendação de cursos personalizados.  
✔️ **Música (Spotify, Deezer, Apple Music)** → Criação de playlists automáticas com base no gosto do usuário.  

---

## **Tecnologias Utilizadas**
✔️ **Python**  
✔️ **Pandas** (Manipulação de dados)  
✔️ **Matplotlib** (Visualizações gráficas)  
✔️ **Surprise** (Biblioteca para sistemas de recomendação)  
✔️ **Scikit-learn** (Validação e métricas)  

---

## **Conclusão**
✔️ **Modelos de recomendação são essenciais** para personalizar a experiência dos usuários e aumentar engajamento.  
✔️ **O modelo SVD foi o mais eficaz**, pois equilibrou precisão, recall e RMSE.  
✔️ **A escolha do modelo depende do contexto** → KNN pode ser útil para relações diretas entre itens, enquanto a Fatoração de Matrizes é mais robusta para dados esparsos.  
✔️ **Este projeto pode ser expandido** para diferentes domínios, como música, e-commerce e aprendizado online.  
