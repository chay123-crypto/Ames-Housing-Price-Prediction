# Ames-Housing-Price-Prediction
This project predicts house prices using the Ames Housing dataset from Kaggle.
It covers an end-to-end machine learning regression pipeline.
Data preprocessing includes missing value treatment and outlier handling.
Numerical features are transformed using log, Box-Cox, and Robust Scaling(due to huge number of outliers).
Categorical features are encoded using One-Hot and frequency encoding.
Feature selection is performed using correlation analysis.
Dimensionality reduction is applied using PCA for efficiency.
Models include Linear Regression, Ridge, Lasso, and SVR.
Hyperparameter tuning is done using GridSearchCV.
Model performance is evaluated using RMSE, MAE, R², and diagnostic plots.
