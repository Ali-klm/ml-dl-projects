Loan Approval Prediction using Random Forest
This project demonstrates a simple machine learning pipeline to predict loan approval status using a Random Forest Classifier. The dataset used is train.csv, which contains customer information such as gender, marital status, education, employment status, and loan details.

Project Overview
Data Preprocessing:

Encoding of categorical variables (e.g., Gender, Married, Education, etc.)

Handling missing values using mode and mean imputation

Feature Scaling:

Standardization of features using StandardScaler

Modeling:

Random Forest Classifier from sklearn is used to train and evaluate the model

Model Evaluation:

F1-Score is used to evaluate performance on both training and testing sets

Feature importance visualization to understand the impact of each feature

Requirements
Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn

How to Use
Clone this repository.

Make sure you have the train.csv file in the project directory.

Run the Python notebook or script to preprocess the data, train the model, and visualize results.