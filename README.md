# Exam Score Prediction

This project predicts student exam performance using survey and behavioral data such as study habits, sleep, attendance, and self-reported preparedness. The goal is to explore which factors are most predictive of exam outcomes and evaluate the performance of different machine learning models.

## Overview

Using a dataset of student responses, multiple features were engineered and analyzed to understand their relationship with exam scores. Both classification and regression approaches were explored to predict performance levels and numeric exam scores.

## Approach

Data cleaning and feature engineering was done via pandas. Exploratory data analysis was then conducted to identify correlations and trends, and drop unimportant features.

### Pass/Fail Classifier

K-Nearest-Neighbors, Support Vector Machine, and Random Forest models were used to classify students as passing/failing. Evaluation was measured with accuracy/precision/recall and visualized with confusion matrices.

### Letter Grade Classifier

K-Nearest-Neighbors, Support Vector Machine, and Random Forest models were then used to classify students as passing/failing. Evaluation was measured with accuracy and visualized with confusion matrices.

### Regression Model

Linear Regression with L2/Ridge regularization was used to predict the exact score of a student. Evaluation was measured with R^2 values, RMSE, and MAE. A residual plot helped visualize the performance.

## Results

The models revealed that factors such as study time, sleep time, and doing class readings are strong predictors of exam performance, while other variables contribute less consistently. 
Model performance reveals the limitations of self-reported data and exam scores being a complex metric with many factors. To improve accuracy, more features and a larger dataset are needed.

## Technologies Used

* Python 

* Pandas, NumPy

* Scikit-learn

* Matplotlib, Seaborn
