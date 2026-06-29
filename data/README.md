# Dados

Esta pasta contém as bases de dados utilizadas no projeto.

## Base original

A base original utilizada neste trabalho é a **Sleep Health and Lifestyle Dataset**, disponível publicamente na plataforma Kaggle.

Caminho no repositório:

```text
data/raw/Sleep_health_and_lifestyle_dataset.csv
```

Fonte: Kaggle — Sleep Health and Lifestyle Dataset
Link: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset

A base original contém informações relacionadas a sono, saúde e estilo de vida, incluindo variáveis como duração do sono, qualidade do sono, nível de estresse, atividade física, categoria de IMC, pressão arterial, frequência cardíaca, passos diários, ocupação e presença de distúrbios do sono.

## Base tratada

A base tratada foi gerada a partir da execução do notebook de análise exploratória.

Caminho no repositório:

```text
data/processed/sleep_health_lifestyle_dataset_treated.csv
```

As principais etapas de tratamento realizadas foram:

* padronização dos nomes das colunas;
* verificação de valores ausentes;
* tratamento dos valores ausentes na coluna `sleep_disorder`;
* preenchimento dos registros sem distúrbio do sono com a categoria `No Sleep Disorder`;
* separação da variável `blood_pressure` em `systolic_pressure` e `diastolic_pressure`;
* criação de uma variável auxiliar indicando se o indivíduo possui ou não distúrbio do sono registrado.

## Observação

A base tratada foi criada apenas para facilitar a análise exploratória. As transformações realizadas não representam diagnóstico clínico nem devem ser interpretadas como inferência estatística.

Os dados devem ser utilizados apenas para fins acadêmicos e exploratórios, respeitando a fonte original disponibilizada no Kaggle.
