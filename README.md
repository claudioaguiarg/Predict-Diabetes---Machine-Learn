# Predição de Detecção de Diabetes

## Descrição do Dataset

Este conjunto de dados provém do Instituto Nacional de Diabetes e Doenças Digestivas e Renais. O estudo e a análise deste conjunto são de extrema importância, dada a relevância crescente da diabetes como uma das doenças crônicas mais prevalentes no mundo. Diagnosticar a diabetes precocemente pode levar a tratamentos mais eficazes e melhores resultados para os pacientes.

O objetivo deste conjunto de dados é oferecer um meio de diagnosticar preditivamente a diabetes em pacientes, com base em medidas diagnósticas específicas. Um destaque especial deste dataset é que ele se concentra em pacientes do sexo feminino com mais de 21 anos de herança Pima Indian.

*Link para o dataset no Kaggle:* [Predict Diabetes Dataset](https://www.kaggle.com/datasets/whenamancodes/predict-diabities)

### Dicionário de Dados e Comentários

| Coluna                      | Descrição                                          | Comentários |
|-----------------------------|----------------------------------------------------|-------------|
| Pregnancies                 | Número de gestações                                | A quantidade de gestações pode influenciar no risco de diabetes. |
| Glucose                     | Nível de glicose no sangue                         | Níveis elevados de glicose são um indicador direto de diabetes. |
| BloodPressure               | Medida da pressão arterial                         | A pressão arterial pode indicar problemas circulatórios comuns em diabéticos. |
| SkinThickness               | Espessura da pele                                  | Alterações na espessura da pele podem ser um sinal de problemas metabólicos. |
| Insulin                     | Nível de insulina no sangue                        | A insulina é fundamental no metabolismo da glicose. Níveis anormais podem indicar diabetes. |
| BMI                         | Índice de massa corporal                           | O IMC elevado é um fator de risco para diabetes tipo 2. |
| DiabetesPedigreeFunction    | Percentual de diabetes                             | Uma função que fornece uma probabilidade baseada na história familiar. |
| Age                         | Idade                                              | A idade é um fator de risco, com a diabetes tipo 2 tornando-se mais comum à medida que as pessoas envelhecem. |
| Outcome                     | Resultado final (1 indica "Sim" e 0 indica "Não")  | A classificação final baseada nas outras variáveis. |

## Organização do Repositório

- dataset/: Pasta contendo o conjunto de dados em formato CSV. Para aqueles interessados em trabalhar diretamente com os dados brutos ou realizar sua própria análise.
- notebooks/: Pasta contendo um notebook detalhado para tratamento dos dados, exibição de gráficos e toda a modelagem de machine learning. Um guia passo a passo para entender o fluxo do projeto.

## Etapas do Projeto

1. *Introdução/Contextualização:* Uma visão geral do problema, enfatizando a importância do diagnóstico precoce e a contribuição deste projeto nesse contexto.
2. *Análise Exploratória de Dados:* Uma profunda imersão nos dados, entendendo cada variável, suas inter-relações e preparando-os para modelagem.
3. *Modelagem:* Um detalhamento de todo o processo de criação do modelo, desde o treinamento até a validação e otimização.

### Modelos de Machine Learning Utilizados

Cada modelo tem suas próprias características e pode oferecer insights diferentes sobre os dados:

- *RandomForestClassifier:* Uma combinação de árvores de decisão que visa melhorar a precisão e evitar o overfitting.
- *Decision Tree (Árvore de Decisão):* Uma representação gráfica de possíveis soluções para um problema, baseada em tomar uma série de decisões.
- *LogisticRegression:* Adequado para classificação binária, tenta prever a probabilidade de uma instância pertencer a uma categoria.
- *KNN (K-Nearest Neighbors):* Classifica com base na maioria da classe de seus 'k' vizinhos mais próximos, sendo útil para identificar padrões não lineares.

## Contribuições

A diabetes é um desafio global e a pesquisa nessa área é fundamental. Este projeto é um esforço colaborativo e a comunidade é encorajada a contribuir. Seja clonando, modificando, ou enviando pull requests, sua contribuição é muito bem-vinda!

## Equipe envolvida no projeto

- Cláudio Aguiar
- Victor Alexandre
- Iris Pires
- Clério Fernandes
