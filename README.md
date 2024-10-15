# Parkinson's UPDRS Prediction

This project aims to predict the Total Unified Parkinson's Disease Rating Scale (UPDRS) score of patients using biomedical voice measures, applying Support Vector Regression (SVR) models with different kernels (RBF and Linear).

## Objective
Predict the total UPDRS score (`total_UPDRS`) from voice measurements of early-stage Parkinson's disease patients.

## Data
The dataset is sourced from a telemonitoring study of 42 patients over six months. The biomedical voice measurements were recorded automatically in the patients' homes.

- Dataset: [Parkinson's Biomedical Voice Data](https://raw.githubusercontent.com/dphi-official/Datasets/master/parkinsons.csv)

## Steps
- Train and evaluate SVR models with different kernels (RBF and Linear).
- Optimize model performance by tuning `C` and `gamma` parameters.
- Compare models based on Mean Squared Error (MSE) and R2 score.
