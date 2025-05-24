# 📉 Identificando e Prevendo Churn em Telecom

Este projeto explora a rotatividade de clientes (churn) no setor de telecomunicações, utilizando análise exploratória de dados (EDA) e modelos preditivos de machine learning para identificar padrões e prever o cancelamento de clientes.

## 🧠 Objetivo

Desenvolver análises e modelos que identifiquem características influenciadoras no churn, permitindo prever quais clientes estão propensos a cancelar os serviços, auxiliando em estratégias de retenção.

## 📊 Dataset

Utilizado o conjunto de dados [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn), contendo informações como:

- **Demográficos**: gênero, idade, presença de dependentes.
- **Serviços**: tipo de contrato, serviços adicionais (TV a cabo, suporte técnico).
- **Financeiros**: valor mensal, cobrança total.
- **Churn**: indicador se o cliente cancelou ou não.

## 🔍 Análise Exploratória (EDA)

Principais insights:

- Clientes com **dependentes** apresentam menor taxa de churn.
- Uso de **fibra óptica** está associado a maior rotatividade.
- Presença de **suporte técnico** reduz a probabilidade de cancelamento.
- Clientes **sem proteção online** têm 1,99 vezes mais chances de cancelar.
- Contratos **mensais** aumentam em 2,06 vezes a chance de churn.

## 🤖 Modelagem Preditiva

Etapas realizadas:

1. Divisão dos dados (out-of-sample).
2. Pré-processamento.
3. Seleção de features.
4. Modelagem e validação.
5. Otimização de hiperparâmetros.
6. Calibração do modelo.

**Resultados:**

- **AUC-ROC**: 86,1% — excelente capacidade discriminativa.
- **Precisão**: 55%, superando em 29 pontos percentuais a baseline aleatória de 26%, representando uma melhoria relativa de 111%.

## ✅ Conclusão

A análise demonstrou que é possível prever o churn com alta precisão, permitindo que empresas de telecomunicações adotem medidas proativas para retenção de clientes, baseando-se em insights obtidos através de dados.

## 📁 Notebooks

- [Análise Exploratória (EDA)](https://github.com/jeanrodovalho16/churn-telecom/blob/main/eda.ipynb)
- [Modelagem Preditiva](https://github.com/jeanrodovalho16/churn-telecom/blob/main/modelagem.ipynb)

## 📝 Artigo Completo

Para uma descrição detalhada do projeto, acesse o artigo no Medium:

[Identificando e Prevendo Churn em Telecom: Insights e Aplicações para Negócios](https://medium.com/@jeanrodovalho16/identificando-e-prevendo-churn-em-telecom-metodologia-insights-e-aplica%C3%A7%C3%B5es-para-neg%C3%B3cios-4fdd0609fddf)

---

