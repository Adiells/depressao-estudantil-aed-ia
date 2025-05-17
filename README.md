# 📘 Previsão e Análise de Depressão em Estudantes Universitários

Este repositório reúne dois notebooks com abordagens complementares voltadas ao estudo de fatores que influenciam a depressão em estudantes universitários. O objetivo central é analisar os dados e investigar formas de **compreender e reduzir os índices de depressão** nesse grupo.

---

## 📁 Estrutura do Repositório

- `analise-depressao.ipynb`: Notebook de **análise exploratória de dados (EDA)** com visualizações, comparações e reflexões sobre possíveis fatores que influenciam a depressão, como estresse financeiro, satisfação com os estudos e carga horária.
  
- `predicao-depressao.ipynb`: Notebook de **machine learning supervisionado**, com a criação e avaliação de modelos preditivos baseados em variáveis comportamentais dos estudantes.

---

## 📊 Sobre o Dataset

O dataset utilizado foi retirado do Kaggle: [`Student Depression Dataset`](https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset). Ele inclui informações como:

- Idade, Gênero, Cidade
- Profissão e Carga Horária de Estudo/Trabalho
- Satisfação com os estudos
- Pressão acadêmica e Estresse financeiro
- Qualidade do sono e hábitos alimentares
- Histórico familiar e pensamentos suicidas

---

## 🧪 Objetivos do Projeto

- Compreender o comportamento da depressão a partir de variáveis observáveis.
- Investigar padrões que **podem sugerir formas de reduzir a incidência de depressão** entre estudantes.
- Criar modelos de machine learning capazes de prever casos de depressão com base em dados comportamentais e influência do ambiente onde os mesmo estão incluidos.

Este projeto é também um marco de aprendizado pessoal, sendo um dos primeiros contatos com as bibliotecas `pandas` e `scikit-learn`, aplicando na prática os conhecimentos em ciência de dados e aprendizado de máquina.

---

## 🔍 Análise Exploratória (EDA)

Através de histogramas e agrupamentos por gênero, faixa etária e outros fatores, foram investigados possíveis gatilhos ou agravantes da depressão. 

---

## 🤖 Modelos de Machine Learning

Três algoritmos supervisionados foram testados:

- Random Forest
- K-Nearest Neighbors (KNN)
- Gradient Boosting

A seleção do modelo final se baseou no desempenho nos dados de teste. O **Gradient Boosting** se destacou, acertando **10 de 14 casos** em dados não vistos.

---

## 🚀 Como Usar

Você pode clonar este repositório e abrir os notebooks no Google Colab ou Jupyter Notebook. Certifique-se de ter:

- Os arquivos `.csv` corretamente carregados.
- Os pacotes Python instalados (`pandas`, `plotly.express`, `scikit-learn`, etc).

---

## 📌 Considerações Finais

Este projeto não pretende oferecer diagnósticos clínicos, mas sim explorar como a ciência de dados pode ajudar a **entender fatores de risco** e auxiliar em políticas de prevenção à depressão universitária.

---

📚 *Projeto desenvolvido com fins educacionais e pessoais para aprofundamento em ciência de dados e IA.*
