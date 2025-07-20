PCA on Iris Dataset
This repository contains a Python script that performs Principal Component Analysis (PCA) on the classic Iris dataset. The dataset is provided as a CSV file named iris.csv.

Overview
The script loads the Iris dataset and extracts the feature columns (sepal length, sepal width, petal length, petal width) along with the species labels.

Features are standardized using StandardScaler to normalize the data.

PCA is applied to reduce the dimensionality of the dataset from 4 features down to 2 principal components.

The transformed data is then visualized in a 2D scatter plot, with each Iris species represented by a different color.

Files
iris.csv: The dataset file containing measurements of Iris flowers and their species.

Python script (not named here): Performs data preprocessing, PCA transformation, and visualization.

This project demonstrates how PCA can be used to visualize high-dimensional data and explore patterns related to different Iris species.