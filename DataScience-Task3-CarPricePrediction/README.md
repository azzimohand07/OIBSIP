# Car Price Prediction

## Overview

This project predicts used car selling prices using Machine Learning.

The workflow includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Linear Regression
- Random Forest Regression
- Model Evaluation

## Dataset

CAR DETAILS FROM CAR DEKHO

## Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Models

- Linear Regression
- Random Forest Regressor

## Evaluation Metrics

- MAE
- RMSE
- R² Score
- Cross Validation

## Results

| Model | MAE | RMSE | R² | CV Mean R² |
|--------|----:|-----:|---:|-----------:|
| Linear Regression | 144,746.31 | 287,517.32 | 0.743 | 0.765 |
| Random Forest* | 0.304 | 0.399 | 0.768 | 0.756 |

> **Note:** Linear Regression MAE and RMSE are reported on the original selling price scale after applying the inverse log transformation. Random Forest MAE and RMSE are currently reported on the log-transformed target, so these values are not directly comparable.