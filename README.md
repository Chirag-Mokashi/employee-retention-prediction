# Employee Retention Prediction — Logistic Regression

A logistic regression model to predict whether an employee is likely to leave an organisation, based on HR and performance features.

## Overview

Employee attrition is costly. This project uses logistic regression to identify which employees are at risk of leaving, helping HR teams take proactive retention steps. The analysis covers data cleaning, feature engineering, model training, and interpretation of key drivers of attrition.

## Problem Statement

Given employee data — satisfaction level, workload, salary band, department, and tenure — predict whether an employee will leave (binary: 0 = stays, 1 = leaves).

## Key Features Used

| Feature | Description |
|---------|-------------|
| `satisfaction_level` | Self-reported satisfaction (0–1) |
| `last_evaluation` | Manager evaluation score |
| `number_project` | Number of projects handled |
| `average_montly_hours` | Average working hours per month |
| `time_spend_company` | Tenure in years |
| `Work_accident` | Whether employee had a workplace accident |
| `promotion_last_5years` | Whether promoted in last 5 years |
| `Department` | Employee department |
| `salary` | Salary band (low / medium / high) |

## Notebook Contents

1. **EDA** — attrition rate by department, salary, satisfaction; correlation analysis
2. **Preprocessing** — encoding categoricals, class imbalance check
3. **Model Training** — logistic regression with scikit-learn
4. **Evaluation** — accuracy, precision, recall, F1, confusion matrix, ROC-AUC
5. **Insights** — which features most strongly predict attrition

## Tech Stack

- Python, Pandas, NumPy
- Scikit-learn (LogisticRegression)
- Matplotlib, Seaborn

## Setup

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Open the notebook from the zip archive in Jupyter or Google Colab.