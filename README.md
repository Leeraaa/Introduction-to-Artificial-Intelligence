# Introduction-to-Artificial-Intelligence

# Housing Price Prediction Using Machine Learning

## Overview

This project was developed as part of the Introduction to Artificial Intelligence course.

The goal of the project is to predict housing prices using machine learning models and advanced feature engineering techniques.

The project compares linear and non-linear machine learning approaches while investigating the impact of feature transformations and regularization.

---

## Dataset

Boston Housing Dataset

Target variable:

- MEDV (Median Home Value)

Features include:

- Crime rate
- Residential land zoning
- Number of rooms
- Distance to employment centers
- Air pollution indicators
- Property tax rates
- Socioeconomic factors

---

## Project Workflow

1. Data Exploration
2. Missing Value Analysis
3. Data Cleaning
4. Feature Engineering
5. Correlation Analysis
6. Multicollinearity Analysis (SVD)
7. Model Training
8. Model Evaluation
9. Model Comparison

---

## Feature Engineering

Several transformations were applied:

- Log Transformation
- Polynomial Features
- Squared Features
- Non-linear Feature Mapping

Examples:

- MEDV → log(MEDV)
- RM → RM²
- DIS → log(DIS)
- LSTAT → log(LSTAT)
- NOX → NOX²

---

## Models Evaluated

### Linear Models

- Ordinary Least Squares (OLS)
- Ridge Regression
- Lasso Regression

### Ensemble Models

- Random Forest Regressor
- XGBoost Regressor

---

## Model Performance

| Model | R² | RMSE | MAE |
|---------|---------|---------|---------|
| OLS | 0.7718 | 0.1886 | 0.1258 |
| Ridge | 0.7716 | 0.1887 | 0.1258 |
| Lasso | 0.7714 | 0.1888 | 0.1257 |
| Random Forest | 0.8260 | 0.1647 | 0.1126 |
| XGBoost | 0.8559 | 0.1499 | 0.1039 |

Best Model:

**XGBoost**

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib
- Seaborn

---

## Skills Demonstrated

- Data Cleaning
- Feature Engineering
- Statistical Analysis
- Regression Modeling
- Regularization Techniques
- Ensemble Learning
- Hyperparameter Optimization
- Model Evaluation
- Machine Learning

---

## Results

XGBoost achieved the best overall performance with:

- R² = 0.8559
- RMSE = 0.1499
- MAE = 0.1039

The project demonstrates the effectiveness of non-linear ensemble methods compared to traditional linear regression approaches for housing price prediction.
