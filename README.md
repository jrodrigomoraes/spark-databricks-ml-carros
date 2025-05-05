# Spark Databricks Machine Learning - Previsão de Potência de Carros

Este projeto utiliza **Apache Spark** e **Databricks** para construir um modelo de **regressão linear** com o objetivo de prever a **potência (HP)** de carros com base em suas características. O modelo é treinado usando dados de carros e avaliado com o **RMSE**.

## Índice

- [Sobre](#sobre)
- [Objetivos](#objetivos)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Pré-requisitos](#pré-requisitos)
- [Como Rodar](#como-rodar)
- [Resultados](#resultados)
- [Licença](#licença)
- [Contato](#contato)

## Sobre

Este repositório contém a implementação de um modelo de **regressão linear** para prever a potência (HP) de carros. O modelo foi treinado utilizando a plataforma **Apache Spark** no **Databricks**, aproveitando o processamento distribuído do Spark.

O dataset utilizado para este projeto está disponível em `datasets/Carros.csv`, e contém informações sobre consumo, cilindrada, número de cilindros, e potência (HP) dos carros.

## Objetivos

- Construir um modelo de **regressão linear** para prever a potência dos carros.
- Utilizar **Apache Spark** para processar grandes volumes de dados.
- Avaliar o modelo utilizando o **RMSE** (Root Mean Squared Error).

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:
```bash
spark-databricks-ml-carros/
├── datasets/
├── notebooks/
├── src/
├── imgs/ 
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```


## Pré-requisitos

Antes de rodar o projeto, é necessário ter o **Python** instalado, juntamente com as dependências especificadas no arquivo `requirements.txt`.

Para instalar as dependências:

```bash
pip install -r requirements.txt
```

Como Rodar:

1. Clone este repositório:
```bash
git clone https://github.com/jrodrigomoraes/spark-databricks-ml-carros.git
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```


5. Execute o notebook Jupyter/Colab para análise exploratória e treinamento do modelo:
```
jupyter notebook notebooks/regressao_linear_carros.ipynb
```

6. Para rodar o código no Databricks, faça o upload dos scripts Python para a plataforma e execute o treinamento lá.

Resultados
A seguir estão as imagens geradas durante o treinamento do modelo, incluindo uma visão geral do banco de dados e os resultados do modelo de regressão linear:

Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
