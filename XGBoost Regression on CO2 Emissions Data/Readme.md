XGBoost Regression on CO2 Emissions Data
This repository contains a Python project demonstrating the use of XGBoost for regression analysis on carbon dioxide (CO2) emissions data. The dataset (CO2.csv) includes historical CO2 emission values with corresponding year and month information.

Overview
The code loads and preprocesses the CO2 emissions dataset.

Features such as Year and Month are extracted and used for modeling.

An XGBoost regressor is trained to predict CO2 emission values.

Model performance is evaluated using cross-validation, RMSE, and R-squared metrics.

Results are visualized through line plots comparing actual vs predicted values and future emission forecasts.

Requirements
Python 3.x

Libraries: xgboost, pandas, numpy, matplotlib, seaborn, scikit-learn

How to Use
Place the CO2.csv dataset in the project directory.

Run the provided Python script to train the model and visualize the results.