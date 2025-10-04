# Redes Neurais - Wine & California Housing

Este projeto explora o uso de redes neurais e algoritmos clássicos de Machine Learning para tarefas de classificação e regressão, utilizando os datasets Wine e California Housing disponíveis na biblioteca scikit-learn. O objetivo é comparar o desempenho de redes neurais criadas com Keras com modelos tradicionais como Random Forest, em cenários distintos de previsão.

## Sobre o Projeto

O repositório apresenta um notebook Jupyter que contém experimentos práticos divididos em dois exercícios principais:

- **Classificação Multiclasse com o Wine Dataset**  
  Utiliza uma rede neural (Keras) e RandomForestClassifier para identificar o tipo de vinho a partir de características físico-químicas.

- **Regressão com o California Housing Dataset**  
  Utiliza uma rede neural (Keras) e RandomForestRegressor para prever o valor médio das casas a partir de dados demográficos e geográficos.

## Principais Tecnologias

- Python 3
- scikit-learn
- TensorFlow & Keras
- Pandas & NumPy
- Jupyter Notebook

## Estrutura do Notebook

- **Introdução**  
  Descrição dos datasets, justificativa da escolha e objetivos dos experimentos.

- **Exercício 1: Classificação Multiclasse (Wine)**  
  - Carregamento dos dados
  - Construção e treinamento dos modelos (Keras NN & RandomForest)
  - Avaliação dos resultados e comparação de acurácia

- **Exercício 2: Regressão (California Housing)**  
  - Carregamento dos dados
  - Construção e treinamento dos modelos (Keras NN & RandomForest)
  - Avaliação dos resultados e comparação dos erros (MAE, RMSE)

- **Discussão dos Resultados**  
  Análise comparativa entre redes neurais e Random Forest nos diferentes cenários.

## Como Executar

1. **Clone o repositório**
   ```bash
   git clone https://github.com/AdonayRocha/Redes_Neurais_WineCalifornia.git
   ```

2. **Instale as dependências**
   ```bash
   pip install -r requirements.txt
   ```
   *(Se não houver um arquivo `requirements.txt`, instale manualmente os pacotes: numpy, pandas, scikit-learn, tensorflow, jupyter)*

3. **Abra o notebook**
   ```bash
   jupyter notebook Redes_Neurais_WineCalifornia.ipynb
   ```
   
## Resultados

Os experimentos mostraram que:

- O **RandomForestClassifier** foi superior à rede neural Keras na tarefa de classificação do Wine Dataset.
- O **RandomForestRegressor** obteve menor erro na tarefa de regressão do California Housing Dataset.

Estes resultados reforçam que algoritmos clássicos ainda são competitivos em cenários com conjuntos de dados tabulares de pequeno a médio porte.

## Autores

- Adonay Rodrigues da Rocha 
- Pedro Henrique Martins Dos Reis
- Thamires Ribeiro Cruz

---

*Este projeto é destinado a fins acadêmicos e de aprendizado sobre redes neurais e comparação de algoritmos de Machine Learning.*
