# Sales Prediction Using Machine Learning

## Overview
This project implements an end-to-end machine learning pipeline to predict retail product sales using a real-world public dataset. 
The objective is to demonstrate ML fundamentals, data preprocessing, model selection, evaluation, and reasoning.

## Dataset
- Public retail sales dataset (BigMart Sales)
- Source: https://www.kaggle.com/datasets/yasserh/bigmartsalesdataset
- Contains numerical and categorical features related to products and outlets

## Approach
1. Data loading and exploration
2. Exploratory Data Analysis (EDA)
3. Data preprocessing (handling missing values, encoding categorical variables)
4. Train-test split
5. Model training
   - Linear Regression 
   - Random Forest Regressor
6. Model evaluation using MAE, RMSE, and R² score
7. Feature importance analysis and inference

## Results
| Model | MAE | RMSE | R² Score |
|------|----|----|----|
| Linear Regression | ~944 | ~1274 | ~0.40 |
| Random Forest | ~760 | ~1094 | ~0.56 |

## Files
- `sales.ipynb` – Complete implementation
- `Sales Prediction.pdf` – Detailed explanation and analysis
