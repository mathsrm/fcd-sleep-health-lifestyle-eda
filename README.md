# Análise Exploratória de Indicadores de Sono, Saúde e Estilo de Vida

Este repositório contém o trabalho prático da disciplina **Fundamentos em Ciências de Dados**, desenvolvido com o objetivo de realizar uma análise exploratória da base **Sleep Health and Lifestyle Dataset**.

O projeto busca observar padrões descritivos e possíveis associações visuais entre variáveis relacionadas ao sono, saúde e estilo de vida, sem realizar inferência estatística, testes de hipótese ou análise causal.

## Base de dados

A base utilizada foi a **Sleep Health and Lifestyle Dataset**, disponível publicamente na plataforma Kaggle.

Link da base: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset

A base contém informações sobre indivíduos e variáveis relacionadas a sono, hábitos de vida e indicadores de saúde, como:

* duração do sono;
* qualidade do sono;
* nível de estresse;
* nível de atividade física;
* categoria de IMC;
* pressão arterial;
* frequência cardíaca;
* passos diários;
* ocupação;
* presença de distúrbios do sono.

## Objetivo do projeto

O objetivo deste trabalho é realizar uma análise exploratória dos dados, buscando observar distribuições, comparar grupos e identificar possíveis padrões na base analisada.

As principais perguntas exploratórias consideradas foram:

* Como se distribuem a duração e a qualidade do sono na base analisada?
* A qualidade do sono apresenta diferenças visuais entre categorias de IMC?
* O nível de estresse apresenta algum padrão visual em relação à qualidade do sono?
* A duração do sono varia de forma descritiva entre diferentes ocupações?
* Pessoas com e sem distúrbio do sono registrado apresentam diferenças descritivas em variáveis como estresse, frequência cardíaca e duração do sono?

## Descrição das pastas

### `data/`

Contém a base de dados original e a base tratada.

* `raw/`: base original baixada do Kaggle.
* `processed/`: base após o tratamento realizado no notebook.

### `notebooks/`

Contém o notebook utilizado para realizar a análise exploratória dos dados.

Arquivo principal:

```text
analise_sono.ipynb
```

### `reports/`

Contém o relatório final do trabalho, elaborado em LaTeX no Overleaf e exportado em PDF.

Arquivo principal:

```text
Relatorio_Final__FCD.pdf
```

### `results/`

Contém os gráficos gerados durante a análise exploratória.

## Etapas realizadas

As principais etapas desenvolvidas no projeto foram:

1. Carregamento da base de dados;
2. Inspeção inicial das variáveis;
3. Verificação de valores ausentes;
4. Tratamento da coluna `Sleep Disorder`;
5. Verificação de duplicidades;
6. Separação da variável `Blood Pressure` em pressão sistólica e diastólica;
7. Construção de tabelas descritivas;
8. Geração de gráficos exploratórios;
9. Interpretação dos principais padrões observados;
10. Discussão das limitações da análise.

## Ferramentas utilizadas

O projeto foi desenvolvido com as seguintes ferramentas:

* Python;
* Google Colab;
* Pandas;
* NumPy;
* Matplotlib;
* Seaborn;
* LaTeX;
* Overleaf;
* GitHub.

## Como executar o notebook

Para reproduzir a análise:

1. Baixe ou clone este repositório;
2. Abra o arquivo `analise_sono.ipynb` no Google Colab ou Jupyter Notebook;
3. Certifique-se de que a base de dados esteja disponível na pasta `data/raw/`;
4. Execute as células do notebook na ordem apresentada.

As bibliotecas necessárias estão listadas no arquivo `requirements.txt`.

Para instalar as dependências em um ambiente local, utilize:

```bash
pip install -r requirements.txt
```

## Observação metodológica

Este projeto tem caráter exclusivamente exploratório. Portanto, os resultados apresentados devem ser interpretados como padrões observados na base analisada.

Não foram realizados:

* testes de hipótese;
* intervalos de confiança;
* modelos preditivos;
* inferência estatística;
* análise causal.

Dessa forma, expressões como “observa-se”, “na base analisada”, “sugere-se” e “possíveis associações” são utilizadas para evitar conclusões fortes ou generalizações indevidas.

## Principais visualizações

A análise exploratória utilizou diferentes tipos de gráficos, incluindo:

* histograma da duração do sono;
* gráfico de barras da qualidade do sono;
* boxplot da qualidade do sono por categoria de IMC;
* gráfico de dispersão entre nível de estresse e qualidade do sono;
* boxplot da duração do sono por ocupação;
* gráfico de barras dos distúrbios do sono por categoria de IMC;
* boxplot da qualidade do sono por presença de distúrbio registrado.

## Relatório

O relatório final está disponível na pasta `reports/`.

Arquivo:

```text
Relatorio_Final__FCD.pdf
```

O relatório apresenta a descrição do problema, a origem dos dados, as etapas de preparação da base, a análise exploratória, os principais resultados observados, as limitações do estudo e a conclusão.

## Autor

Matheus Sanches Raimundo Mendonça

## Disciplina

**Fundamentos em Ciências de Dados**
Instituto de Ciências Matemáticas e de Computação — ICMC
Universidade de São Paulo — USP
1º semestre de 2026
