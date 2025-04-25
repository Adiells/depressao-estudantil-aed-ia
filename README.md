# Previsão de Depressão em Estudantes

Este repositório contém dois notebooks (um ainda a ser adiconado) com abordagens diferentes voltadas ao estudo e análise de dados de um conjunto sobre estudantes universitários e sinais de depressão.

## 📁 Estrutura do repositório

- `analise-depressao.ipynb`: Análise exploratória dos dados (**AED - Algoritmos e Estruturas de Dados**), com visualizações e observações estatísticas importantes.
- `predicao-depressao.ipynb`: Aplicação de algoritmos de **Inteligência Artificial** para prever a presença de depressão entre os estudantes com base em variáveis comportamentais e demográficas.

## 📊 Sobre o Dataset

O dataset utilizado é o [`Student Depression Dataset`](https://www.kaggle.com/datasets/adilshamim8/student-depression-dataset), disponível no Kaggle. Ele contém dados sobre estudantes, como:

- Gênero
- Idade
- Cidade
- Profissão
- Hábitos alimentares
- Duração do sono
- Estresse financeiro
- Histórico familiar de doenças mentais
- Pensamentos suicidas
- e outros fatores relevantes

O objetivo principal é analisar esses dados e desenvolver modelos capazes de prever a condição de depressão com base na identificação de padrões e nos fatores apresentados.

## 🤖 Modelos Utilizados

No notebook de IA, foram testados três algoritmos:

- Random Forest
- K-Nearest Neighbors (KNN)
- Gradient Boosting (GB)

A escolha final foi feita com base na acurácia de cada modelo sobre os dados de teste.

## ✅ Resultado

O modelo final (Gradient Boosting) obteve um bom desempenho na tarefa de previsão, com acerto de aproximadamente **10 em 14** casos analisados em um conjunto de dados novos.

## 🧠 Objetivo

Esse projeto foi criado com fins de aprendizado e prática de conceitos de ciência de dados, pré-processamento, e machine learning supervisionado com a biblioteca `scikit-learn`. Com esse projeto sendo, inclusive, meu primeiro com as bibliotecas pandas e scikit-learn, o foco foi entender como funcionam os algoritmos de aprendizado de máquina e como aplicá-los em um conjunto de dados real.

## 🚀 Como usar

Você pode clonar este repositório e abrir os notebooks no Google Colab ou Jupyter Notebook. Certifique-se de ter os arquivos `.csv` disponíveis e os pacotes do Python instalados.

---