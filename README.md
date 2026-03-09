# Telecom X - Previsão de Churn (Machine Learning)

## Sobre o Projeto

Este projeto tem como objetivo prever a evasão de clientes (churn) em uma empresa de telecomunicações utilizando técnicas de Machine Learning.

A análise busca identificar padrões no comportamento dos clientes que indicam maior probabilidade de cancelamento de serviços, permitindo que a empresa implemente estratégias de retenção mais eficazes.

---

## Objetivos

- Preparar os dados para modelagem
- Aplicar técnicas de pré-processamento
- Treinar modelos de Machine Learning
- Avaliar o desempenho dos modelos
- Identificar fatores que influenciam a evasão de clientes

---

## Dataset

O conjunto de dados contém informações sobre clientes da empresa Telecom X, incluindo:

- Informações demográficas
- Tipo de contrato
- Serviços contratados
- Valor da mensalidade
- Tempo de permanência
- Histórico de evasão

Total de registros analisados: **7032 clientes**

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

## Modelos de Machine Learning

Foram utilizados dois modelos de classificação:

### Regressão Logística
Modelo linear utilizado para estimar a probabilidade de churn.

### Random Forest
Modelo baseado em ensemble de árvores de decisão capaz de capturar relações mais complexas entre as variáveis.

---

## Avaliação dos Modelos

Os modelos foram avaliados utilizando as seguintes métricas:

- Acurácia
- Precisão
- Recall
- F1-score
- Matriz de confusão

A comparação entre os modelos permitiu identificar aquele com melhor capacidade de prever a evasão de clientes.

---

## Principais Fatores de Churn

A análise indicou que alguns fatores possuem forte relação com a evasão de clientes:

- Tipo de contrato
- Tempo de permanência (tenure)
- Valor da mensalidade
- Tipo de serviço de internet
- Método de pagamento

Clientes com contratos mensais e menor tempo de permanência apresentaram maior probabilidade de cancelamento.

---

## Insights Estratégicos

Com base nos resultados, algumas estratégias podem ajudar a reduzir o churn:

- Incentivar contratos de longo prazo
- Criar programas de retenção para novos clientes
- Revisar planos com mensalidades mais elevadas
- Melhorar a experiência do cliente em serviços críticos

---

## Estrutura do Projeto

TelecomX - Parte 2
│
├── TelecomX_2.ipynb
├── telecomx_tratado.csv
└── README.md

---

## 👨‍💻 Autor

Gustavo Mendes  
Projeto desenvolvido como parte do desafio de análise de dados e Machine Learning da Telecom X.
