# Mall Customer Segmentation using K-Means Clustering

## Overview
This project applies K-Means clustering to segment mall customers based on their demographic and spending attributes. By analyzing features such as Age, Annual Income, and Spending Score, we aim to identify distinct customer groups to inform targeted marketing strategies.

## Dataset
Source: Mall Customer Segmentation Data from Kaggle

Features: 4 Features (CustomerID, Gender, Age, Annual Income, Spending Score)

## Steps Covered
1. Loaded the dataset and performed initial exploration to understand the structure and summary statistics.
2. Standardized features using StandardScaler to ensure equal weightage.
3. Utilized the Elbow Method to identify the optimal number of clusters (K).
4. Calculated inertia for K values ranging from 1 to 10.
5. Applied K-Means clustering with the chosen K value and assigned cluster labels to each customer.
6. Used PCA for dimensionality reduction to visualize clusters in 2D space.
7. Plotted clusters to interpret the segmentation.
8. Calculated the Silhouette Score to assess the quality of clustering.


## Results
Identified distinct customer segments based on age, income, and spending score.

Visualizations provided clear insights into customer groupings.

Achieved a Silhouette Score of [insert score], indicating [interpretation] clustering performance.
