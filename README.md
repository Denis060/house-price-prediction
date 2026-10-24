# House Price Prediction — Regression Baselines

> A course project comparing Linear Regression, Random Forest and Decision Tree regressors for house prices, and diagnosing why all three explain very little variance.

[![Python](https://img.shields.io/badge/Python-3-blue.svg)](https://www.python.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Overview & motivation

Given property attributes (living area, bedrooms, bathrooms, above-ground area, year built), how well can standard models predict sale price? The project walks through cleaning, EDA, feature selection, modeling and evaluation.

## Approach & tech stack

1. Cleaning & wrangling (missing values, types, scaling)
2. EDA of key features vs. price
3. Feature selection: `sqft_living`, `bedrooms`, `bathrooms`, `sqft_above`, …
4. Models: Linear Regression, Random Forest, Decision Tree; evaluated with MSE and R²

**Stack:** Python · pandas · scikit-learn · Matplotlib/Seaborn

## Results

| Model | R² (test) |
|---|---:|
| Linear Regression | ~0.03 |
| Random Forest | ~0.02 |
| Decision Tree | < 0 |

All models explain only a few percent of price variance on this dataset; the Decision Tree overfits. The lesson: model choice matters far less than features — drivers available in the data but not used here (location/zip code, condition, view, waterfront) and outlier handling are the obvious next steps.

## How to run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
python house_price.py     # or open Assignment_2_Ibrahim_Denis_fofanah.ipynb
```
Data: `data_assignment2.csv` (semicolon-delimited).

---

## About the author

**Ibrahim Denis Fofanah** — Data Scientist · ML / GenAI (RAG, agents) · BI & analytics · MS Data Science, Pace University (2025)

[LinkedIn](https://www.linkedin.com/in/ibrahim-denis-fofanah/) · [Email](mailto:ibrahim.fofanah.ds@gmail.com) · [Live RAG portfolio project](https://moijey-copilot.vercel.app) · [GitHub](https://github.com/Denis060)
