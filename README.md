# ✈️ Previsão de Atraso de Voos

Este projeto tem como objetivo prever o tempo estimado de atraso de voos com base em dados históricos. O processo envolveu desde a análise exploratória até a construção e otimização de modelos de machine learning.

## 📊 Aprendizados e Etapas do Projeto

Durante o desenvolvimento deste projeto, aprendi e pratiquei diversas técnicas essenciais de ciência de dados:

### 📌 Análise dos Dados
- Análise de estatísticas descritivas (média, mediana, desvio padrão, etc.).
- Inspeção de valores nulos e verificação da tipagem de cada coluna.
- Criação de visualizações gráficas para compreender a distribuição e correlação dos dados.
- Criação de novas colunas a partir de colunas existentes.
- Transformação de variáveis categóricas com `get_dummies`.

### 🧹 Pré-processamento
- Limpeza dos dados, mantendo apenas colunas úteis para a regressão.
- Eliminação de colunas com baixa correlação ou relevância.

### 🧠 Modelagem de Machine Learning
- Construção de um modelo **baseline** utilizando regressão linear.
- Avaliação do modelo utilizando métricas:
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)
  - R² (Coeficiente de Determinação)
- Implementação de um modelo mais robusto com **RandomForestRegressor**.
- Avaliação gráfica da performance do modelo.

### 🔍 Validação e Otimização
- Validação cruzada (cross-validation) para verificar a generalização do modelo.
- Seleção das features mais importantes para reduzir complexidade sem perda de desempenho.
- Otimização de hiperparâmetros com **GridSearchCV**.

### 💾 Salvamento do Modelo
- Modelo final treinado e salvo para futuras previsões.

---

👨‍💻 Projeto desenvolvido como parte da minha jornada de estudos em Ciência de Dados e Machine Learning.

