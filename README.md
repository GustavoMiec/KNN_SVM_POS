# 📊 Projeto de Análise e Classificação de Recrutamento

Este projeto tem como objetivo analisar dados de recrutamento, realizar tratamento, explorar padrões e treinar modelos de Machine Learning para prever o status de contratação de candidatos.

---

## 📂 Estrutura do Projeto

- **Exploração dos Dados**
  - Visualização de valores ausentes com `missingno`
  - Análises estatísticas descritivas
  - Distribuições e boxplots das variáveis
  - Matrizes de correlação (Seaborn Heatmap)
  - Visualizações com `seaborn` e `plotly-express`

- **Pré-processamento**
  - Tratamento de valores nulos
  - Codificação de variáveis categóricas (`LabelEncoder` e `get_dummies`)
  - Normalização e padronização de dados (`StandardScaler`)

- **Modelagem**
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM) com `LinearSVC` e `SVC (poly kernel)`
  - Comparação de métricas de desempenho

- **Avaliação**
  - Acurácia
  - Curva ROC e AUC
  - Relatórios de erro médio por valor de *K*

---

## 🚀 Tecnologias Utilizadas

- **Python 3.x**
- **Bibliotecas**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `plotly-express`
  - `missingno`
  - `scikit-learn`

---

## 📈 Resultados Esperados

- Identificação de padrões entre variáveis (notas, experiências, especializações e salários)
- Previsão do status de contratação (`status`) com modelos de ML
- Comparação de desempenho entre KNN e SVM

---

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/projeto-recrutamento.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook ou script principal:
   ```bash
   jupyter notebook recrutamento.ipynb
   ```
   ou
   ```bash
   python recrutamento.py
   ```

---

## 📌 Observações

- O dataset utilizado foi disponibilizado em formato `Recrutamento.xlsx`.
- Alguns gráficos interativos usam `plotly-express` para melhor visualização.
- O modelo final pode variar em desempenho conforme o pré-processamento escolhido.

---

## ✨ Autor

Projeto desenvolvido por **[Gustavo Costa]** como prática de **Análise de Dados e Machine Learning**.
