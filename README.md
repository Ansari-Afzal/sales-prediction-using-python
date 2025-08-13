# Sales Prediction Using Python

A Jupyter Notebook–based project that predicts sales using advertising data and machine learning in Python.

---

##  Project Overview

This repository demonstrates a straightforward approach to predicting product sales based on advertising expenditures. You'll find:

- **Advertising.csv** – Dataset containing advertising spend across various channels and associated sales figures.
- **sales prediction using python.ipynb** – Jupyter Notebook that walks through data exploration, model building, evaluation, and interpretation.

---

##  Objectives

- Explore relationships between advertising channels and sales through exploratory data analysis (EDA).
- Train and evaluate regression models to forecast sales.
- Select and analyze the best-performing model based on evaluation metrics.

---

##  Dataset Description

| Column    | Description                             |
|-----------|-----------------------------------------|
| TV        | Advertising budget for TV               |
| Radio     | Advertising budget for radio            |
| Newspaper | Advertising budget for newspapers       |
| Sales     | Sales revenue (target variable)         |

*(Verify that these column names and descriptions match your dataset.)*

---

##  Methodology

1. **Data Loading & Inspection** – Load CSV, check missing values, review basic stats.
2. **EDA** – Visualize trends, correlations, and relationships between features.
3. **Model Training** – Apply regression models (Linear Regression, Random Forest, etc.).
4. **Evaluation** – Assess performance using RMSE, MAE, and R².
5. **Insights** – Identify which channels most influence sales.

---

##  Dependencies

This project uses:

- Python 3.6+
- pandas
- NumPy
- Matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

Install them via:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
