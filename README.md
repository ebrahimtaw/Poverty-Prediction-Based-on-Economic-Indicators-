# Poverty Prediction Based on Economic Indicators 📊

This project aims to predict the **probability** of a country being poor using logistic regression, based on various economic indicators.

## Dataset:
- Sourced from [Kaggle](https://www.kaggle.com/datasets/ophi/mpi)

## Features:
- **MPI Urban**: Multi-dimensional poverty index for urban areas.
- **Headcount Ratio Urban**: Percentage of the population listed as poor in urban areas.
- **Intensity of Deprivation Urban**: Average poverty depth for the poor in urban areas.
- **MPI Rural**: Multi-dimensional poverty index for rural areas.
- **Headcount Ratio Rural**: Percentage of the population listed as poor in rural areas.
- **Intensity of Deprivation Rural**: Average poverty depth for the poor in rural areas.

## Target Variable:
- **High Poverty Probability**: The predicted probability of whether a country is likely to be below the poverty line. A higher probability indicates a higher likelihood of being in poverty.

## Technical Overview:
- **Input Data**: Economic indicators for urban and rural areas.
- **Model**: Logistic regression to predict the probability of high poverty.
- **Metrics**: Accuracy, precision, recall, F1-score.

## Highlights:
- Analyzes poverty across both rural and urban areas.
- Logistic regression model predicts the **probability** of high poverty.
- Decision boundary visualizations for urban and rural poverty indicators.

## Key Steps:
1. Data Analyses.
2. Define target variable: **Probability of high poverty** based on economic indicators.
3. Train-test split (80% train, 20% test).
4. Model training using logistic regression.
5. Evaluate performance using accuracy, precision, recall, F1-score, and ROC-AUC.
6. Visualize decision boundaries for urban and rural indicators.

Explore the code to learn how machine learning aids in forecasting economic metrics! 🚀
