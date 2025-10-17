# Iris Data Analysis — PCA & GMM Clustering

This project explores the Iris flower dataset using data preprocessing, Principal Component Analysis (PCA) for dimensionality reduction, and Gaussian Mixture Model (GMM) for clustering.

The goal is to demonstrate a complete unsupervised learning pipeline — from cleaning and scaling data to visualizing meaningful clusters in a reduced feature space.
## Dataset
Iris Dataset — a classic dataset containing measurements of 150 iris flowers from three species:
Iris Setosa
Iris Versicolor
Iris Virginica
Features:
Sepal Length
Sepal Width
Petal Length
Petal Width
## Workflow Overview
1. Data Preprocessing
Loaded the dataset using sklearn.datasets or ucimlrepo.
Checked for missing values and data consistency.
Outlier Detection:
Applied the IQR method to detect outliers in numerical features.
Removed detected outliers for cleaner clustering results.

Feature Scaling:

Used StandardScaler to normalize numerical columns for PCA and GMM.

2. Dimensionality Reduction (PCA)

Applied Principal Component Analysis (PCA) to reduce the data from 4D to 2D.

Retained 95% of variance while simplifying visualization.

Visualized the first two principal components.

3. Clustering (GMM)

Applied Gaussian Mixture Model (GMM) clustering on PCA-transformed data.

Compared clustering results with true species labels.

Visualized clusters using color-coded scatter plots.
