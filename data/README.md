# Data

This folder contains the datasets used in the project.

## Original dataset

Path:

```text
data/raw/Sleep_health_and_lifestyle_dataset.csv
```

Source: Kaggle — Sleep Health and Lifestyle Dataset  
Link: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset

## Treated dataset

Path:

```text
data/processed/sleep_health_lifestyle_dataset_treated.csv
```

The treated dataset was generated in the notebook after the preprocessing steps. The main transformations were:

- standardization of column names;
- treatment of missing values in the `sleep_disorder` column;
- creation of `systolic_pressure` and `diastolic_pressure` from `blood_pressure`;
- creation of a grouping variable indicating whether a sleep disorder was registered.
