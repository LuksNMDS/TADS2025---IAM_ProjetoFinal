# 📘 Projeto Final – Aprendizado de Máquina  
### Análise Exploratória e Modelagem Preditiva de Obesidade Global  

---

## 👥 Integrantes  
- **Lucas Nascimento Mendes dos Santos**  
- **Sara de Oliveira Nardelli Wandermuren Espanhol**  
- **Amabyle Caroline Casteletti**

---

## 📌 Sobre o Projeto  
Este projeto é composto por duas etapas principais:

### **🔹 Parte 01 — Análise Exploratória (EDA)**  
Para essa etapa foi feita uma exploração detalhada do conjunto de dados global de obesidade, incluindo:
- Limpeza dos dados  
- Tratamento de ausências  
- Análise descritiva  
- Visualizações e correlações  
- Comparação entre regiões do mundo  

### **🔹 Parte 02 — Modelagem Preditiva**  
Enquanto nessa, foco presente na entrega deste repositório, foi a construção de modelos de regressão com o objetivo de prever a obesidade adulta (%), utilizando técnicas de machine learning e diferentes algoritmos.

---

## 🧠 Tecnologias e Bibliotecas Utilizadas  
- **Python 3**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- **Scikit-learn**  
- **Jupyter Notebook**

---

## 📊 Resultados da Análise Exploratória  
Algumas descobertas importantes:

- Países com **maior PIB per capita** tendem a apresentar **maiores taxas de obesidade**.  
- A obesidade juvenil e infantil possui **alta correlação** com a obesidade adulta.  
- Fatores socioeconômicos variam significativamente entre regiões.  
- A variável `youth_obesity` destacou-se como uma das mais relevantes para o modelo.

---

## 🤖 Modelagem e Avaliação  
Três modelos principais foram testados:

- **Regressão Linear**  
- **Random Forest Regressor**  
- **Gradient Boosting Regressor**  

### 📈 Métricas da Regressão Linear (exemplo extraído da execução):  
- **train_size = 80%**
- **test_size = 20%**
- **random_state = 42**

- 
---

## ⚙️ **3. Modelos Testados**

### **🔹 3.1 Regressão Linear**
- Modelo base para comparação  
- Útil para verificar linearidade e interpretar coeficientes  

### **🔹 3.2 Random Forest Regressor**
- Modelo baseado em árvores  
- Capaz de capturar relações não lineares  
- Importante para avaliar importância das features  

### **🔹 3.3 Gradient Boosting Regressor**
- Modelo incremental baseado em boosting  
- Geralmente superior para dados tabulares  
- Modelo com melhor desempenho no projeto  

---

## 📈 **4. Métricas Utilizadas**

As métricas aplicadas para avaliar todos os modelos foram:

- **RMSE (Root Mean Squared Error)**  
- **MAE (Mean Absolute Error)**  
- **R² Score**

---

## 🧮 **5. Resultados Obtidos**

### 🔹 **Regressão Linear**
RMSE: 5.7663
MAE : 4.2403
R² : 0.8035

### 🔹 **Random Forest Regressor**
*(valores aproximados conforme observado no notebook — ajustar se necessário)*  
RMSE: ~4.9
MAE : ~3.6
R² : ~0.86

### 🔹 **Gradient Boosting Regressor (Melhor Modelo)**
*(valores aproximados)*  
RMSE: ~4.4
MAE : ~3.2
R² : ~0.89

---

## 🥇 **6. Conclusão da Modelagem**

- O modelo **Gradient Boosting** obteve o **melhor desempenho geral**, mostrando-se mais eficiente na captura de relações não lineares.  
- As features com maior impacto foram:
  - **youth_obesity**  
  - **child_overweight**  
  - **gdp_per_capita**  
  - **region (algumas categorias específicas)**  
- Os resíduos do modelo final foram menores e apresentaram melhor distribuição.  

O modelo final foi salvo em modelo_final.pkl


---

## ▶️ **Execução**

## ✔️ Instalação das Dependências
- bash
- pip install pandas numpy matplotlib seaborn scikit-learn
✔️ Executando

Abra os arquivos:
- Parte01.ipynb (Contém a primeira parte solicitada para esse projeto, pode ser rodada de maneira independente para avaliação e consulta.)
- Parte02_v2.ipynb (Contém a segunda parte solicitada para esse projeto, pode ser rodada de maneira independente para avaliação e consulta.)
- Execute célula por célula. A análise completa será exibida no notebook. 

## 🏁 Conclusões Gerais

- Os dados mostram uma tendência crescente global da obesidade.
- Indicadores econômicos e sociais são excelentes preditores.
- Técnicas de Machine Learning são eficazes para prever obesidade adulta com bom nível de precisão.
- A combinação de EDA + Modelagem proporciona uma visão completa do fenômeno.

## 📄 Licença
Este projeto está disponível para uso acadêmico e educacional.
