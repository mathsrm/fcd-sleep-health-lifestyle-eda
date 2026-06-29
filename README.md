# Sleep Health and Lifestyle EDA

This repository contains an **Exploratory Data Analysis (EDA)** project developed for the course **Fundamentos em Ciências de Dados**.

The project explores the **Sleep Health and Lifestyle Dataset**, observing descriptive patterns and possible visual associations between variables related to sleep, health, and lifestyle.

## Repository link

https://github.com/mathsrn/fcd-sleep-health-lifestyle-eda

## Dataset

The dataset used in this project is the **Sleep Health and Lifestyle Dataset**, available on Kaggle:

https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset

The dataset includes variables such as:

- sleep duration;
- quality of sleep;
- stress level;
- physical activity level;
- BMI category;
- blood pressure;
- heart rate;
- daily steps;
- occupation;
- sleep disorder status.

Both the original dataset and the treated dataset are available in this repository:

```text
data/raw/Sleep_health_and_lifestyle_dataset.csv
data/processed/sleep_health_lifestyle_dataset_treated.csv
```

## Project objective

The objective is to perform an exploratory analysis of variables related to sleep, health, and lifestyle. The analysis focuses on questions such as:

- How are sleep duration and quality of sleep distributed?
- Are there visual differences in quality of sleep between BMI categories?
- Is there a visual pattern between stress level and quality of sleep?
- Does sleep duration vary descriptively across occupations?
- Are there descriptive differences between individuals with and without registered sleep disorders?

## Repository structure

```text
fcd-sleep-health-lifestyle-eda/
│
├── data/
│   ├── raw/                      # Original dataset
│   └── processed/                # Treated dataset
│
├── notebooks/
│   └── analise_sono.ipynb        # Google Colab notebook
│
├── reports/
│   └── Relatorio_Overleaf.pdf    # Final report exported from Overleaf
│
├── results/                      # Figures generated during the analysis
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Notebook

The analysis notebook is available at:

```text
notebooks/analise_sono.ipynb
```

After pushing this repository to GitHub, the notebook can be opened directly in Google Colab using:

https://colab.research.google.com/github/mathsrn/fcd-sleep-health-lifestyle-eda/blob/main/notebooks/analise_sono.ipynb

## Results

The `results/` folder contains the figures generated in the exploratory analysis:

| File | Description |
|---|---|
| `sleep_duration_distribution.png` | Distribution of sleep duration |
| `sleep_quality_frequency.png` | Frequency of quality of sleep levels |
| `sleep_quality_by_bmi_category.png` | Quality of sleep by BMI category |
| `stress_level_vs_sleep_quality.png` | Stress level versus quality of sleep |
| `sleep_duration_by_occupation.png` | Sleep duration by occupation |
| `sleep_disorder_by_bmi_category.png` | Sleep disorder status by BMI category |
| `sleep_quality_by_sleep_disorder_status.png` | Quality of sleep by sleep disorder status |

## Tools used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- LaTeX / Overleaf
- GitHub

## Methodological note

This project is exclusively exploratory. Therefore, the results should be interpreted as descriptive patterns observed in the analyzed dataset.

No statistical inference, hypothesis testing, predictive modeling, or causal analysis was performed.

Expressions such as **observed**, **in the analyzed dataset**, **suggests**, and **possible associations** are used to avoid strong conclusions or causal interpretations.

## Author

- Matheus Sanches Raimundo Mendonça
