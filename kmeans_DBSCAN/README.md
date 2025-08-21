# Customer Segmentation using K-Means and DBSCAN

This project explores customer segmentation using two clustering algorithms: K-Means and DBSCAN.

## Data
The dataset used is 'Mall_Customers.csv', containing customer information such as Gender, Age, Annual Income, and Spending Score.

## Analysis
- Data loading and initial exploration (EDA).
- Age categorization.
- K-Means clustering on Annual Income and Spending Score.
- DBSCAN clustering on Annual Income and Spending Score.
- Silhouette score evaluation for both models.

## Results
The K-Means model with 5 clusters shows a better silhouette score (0.55) compared to the DBSCAN model with the chosen parameters (0.48). Visualizations of the clusters are included.

## Requirements
See `requirements.txt` for dependencies.
