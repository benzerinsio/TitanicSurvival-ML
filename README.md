# 🚢 Previsão de Sobrevivência no Titanic
*Projeto de Machine Learning - Felipe V. Sousa*

Bem-vindo(a)! Este repositório apresenta uma análise completa da competição Titanic do Kaggle, combinando pré-processamento avançado, feature engineering e modelagem de Machine Learning para prever a sobrevivência dos passageiros com alta precisão.

🔗 [Visualizar o Notebook](https://github.com/benzerinsio/TitanicSurvival-ML/blob/main/ML_Titanic.ipynb)

## 🎯 Objetivo da Análise

Analisar o dataset Titanic para prever a sobrevivência dos passageiros, utilizando técnicas de pré-processamento detalhado, feature engineering baseado em títulos e avaliação de múltiplos modelos de Machine Learning. O foco é identificar fatores-chave (ex.: classe, sexo, idade) e alcançar um desempenho competitivo na submissão ao Kaggle.

## 📊 Fonte de Dados

Dados da competição Titanic (Kaggle), com 891 registros de treino (12 colunas, incluindo `Survived`) e 418 registros de teste para previsão.

## 🛠️ Bibliotecas Utilizadas

- **Pandas**: Manipulação e pré-processamento de dados.  
- **Scikit-learn**: Modelos de ML, GridSearchCV e métricas de avaliação.  
- **Seaborn**: Visualizações estatísticas (ex.: matriz de correlação).  
- **Matplotlib**: Gráficos complementares.  
- **StandardScaler**: Normalização para modelos sensíveis à escala.

## 💬 Conclusão

Este projeto implementa uma pipeline robusta: limpeza de dados (remoção de `Cabin`, `Ticket`, tratamento de `Age`), feature engineering (títulos extraídos de `Name`) e avaliação de modelos (Regressão Logística, Random Forest, Decision Tree, SVM). O SVM (`C=1`, `gamma=0.1`, `kernel='rbf'`) destacou-se com o melhor desempenho combinado em validação cruzada e conjunto de validação, gerando uma submissão competitiva. O notebook, otimizado para visualização via nbviewer, oferece uma base sólida para futuros ajustes, como ensembles avançados ou feature engineering adicional.