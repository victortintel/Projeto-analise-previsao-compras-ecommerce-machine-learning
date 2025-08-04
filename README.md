# 🛍️ Análise e Previsão de Compras em E-commerce com Machine Learning

Este projeto explora dados de comportamento de usuários em um site de e-commerce para prever a probabilidade de compra em uma sessão. Utilizando técnicas de machine learning supervisionado e manipulação de dados com Python, o objetivo foi identificar os principais fatores que influenciam a geração de receita (variável Revenue) e construir modelos preditivos eficazes para apoiar estratégias de marketing digital e otimização de conversão.

O projeto foi inteiramente desenvolvido em Python com foco em aprendizado de máquina aplicado ao negócio, incluindo:

Engenharia de atributos,

Balanceamento de classes,

Testes de diferentes modelos preditivos,

Avaliação com métricas como F1, AUC, precisão e recall.
---

## 📌 Sobre o Projeto

- **Título:** Previsão de Vendas em E-commerce com Machine Learning  
- **Autor:** Victor Tintel  
- **Dataset:** [Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset)  
- **Registros:** 12.330 sessões únicas  
- **Variável alvo:** `Revenue` (booleano: True = houve compra)  

---

## 🎯 Objetivo de Negócio

Identificar os principais fatores que levam um usuário a realizar uma compra e construir um modelo preditivo que apoie ações estratégicas de marketing e vendas no e-commerce.

---

## 📊 Etapas Desenvolvidas

### 1. Análise Exploratória de Dados (EDA)
- Visualização de distribuições  
- Correlações entre variáveis  
- Dicionário de dados comentado  

### 2. Pré-processamento
- Normalização: `StandardScaler`, `QuantileTransformer`  
- Codificação: `OneHotEncoder`  
- Balanceamento de classes: `SMOTE`  
- Divisão treino/teste  

### 3. Modelagem Preditiva
Modelos utilizados:
- Support Vector Machine (SVM)  
- Random Forest  
- XGBoost ✅ (modelo com melhor performance)  

### 4. Avaliação
- Métricas: Accuracy, Precision, Recall, F1-Score, AUC  
- Curva ROC  
- Comparação entre modelos  

---

## 🔍 Principais Insights

- Visitantes recorrentes têm maior chance de realizar compras.  
- Páginas com alto valor de conteúdo e menor taxa de saída estão associadas a maiores conversões.  
- Proximidade com datas especiais (ex: Dia dos Namorados) influencia diretamente a decisão de compra.  

---

## ⚙️ Tecnologias e Ferramentas

| Categoria             | Ferramentas                                      |
|-----------------------|--------------------------------------------------|
| Linguagem             | Python                                           |
| Bibliotecas de ML     | `scikit-learn`, `xgboost`, `imblearn`            |
| Visualização          | `matplotlib`, `seaborn`                          |
| Manipulação de Dados  | `pandas`, `numpy`                                |
| Pré-processamento     | `StandardScaler`, `QuantileTransformer`          |
| Balanceamento         | `SMOTE`                                          |

---
