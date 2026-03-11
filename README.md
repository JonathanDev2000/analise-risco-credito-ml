# Análise de Risco de Crédito com Machine Learning

<p align="left">
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

## Sobre o Projeto

Projeto de TCC desenvolvido para predição de risco de crédito utilizando técnicas de Machine Learning. O objetivo é classificar solicitações de crédito como **baixo** ou **alto risco**, auxiliando instituições financeiras na tomada de decisões.

O projeto segue a metodologia **CRISP-DM** (Cross Industry Standard Process for Data Mining), passando pelas etapas de entendimento do negócio, análise exploratória, pré-processamento, modelagem e avaliação.

---

## Metodologia: CRISP-DM

```
1. Entendimento do Negócio
   └─ Definir o problema de classificação de risco de crédito

2. Entendimento dos Dados
   └─ Análise Exploratória de Dados (EDA)

3. Preparação dos Dados
   └─ Tratamento de valores nulos, encoding, normalização

4. Modelagem
   └─ Regressao Logística, Random Forest, Gradient Boosting

5. Avaliação
   └─ Métricas: Acurácia, Precisão, Recall, F1-Score, ROC-AUC

6. Implantação
   └─ Relatório final e documentação
```

---

## Tecnologias Utilizadas

| Tecnologia | Versão | Finalidade |
|---|---|---|
| Python | 3.10+ | Linguagem principal |
| Pandas | 2.x | Manipulação de dados |
| NumPy | 1.x | Operações numéricas |
| Scikit-learn | 1.x | Modelos de Machine Learning |
| Matplotlib / Seaborn | - | Visualização de dados |
| Jupyter Notebook | - | Ambiente de desenvolvimento |
| Google Colab | - | Execução na nuvem |

---

## Modelos Avaliados

- Regressão Logística
- Random Forest Classifier
- Gradient Boosting (XGBoost)
- KNN (K-Nearest Neighbors)

---

## Métricas de Avaliação

- **Acurácia** — percentual de acertos geral
- **Precisão** — dos classificados como risco, quantos realmente são
- **Recall** — dos que são risco, quantos o modelo detectou
- **F1-Score** — média harmônica entre precisão e recall
- **ROC-AUC** — capacidade discriminativa do modelo

---

## Como Executar

```bash
# Clone o repositório
git clone https://github.com/JonathanDev2000/analise-risco-credito-ml.git

# Instale as dependências
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# Execute o Jupyter Notebook
jupyter notebook
```

Ou acesse diretamente pelo **Google Colab** clicando no badge de cada notebook.

---

## Status do Projeto

- [x] Definição do problema
- [x] Coleta e análise exploratória dos dados
- [ ] Pré-processamento e feature engineering
- [ ] Treinamento e comparação de modelos
- [ ] Avaliação final e relatório

---

## Autor

**Jonathan Reis**  
Curso: Ciência de Dados / TCC  
[LinkedIn](https://www.linkedin.com/in/jonathan-reis-a906771a1) · [GitHub](https://github.com/JonathanDev2000)
