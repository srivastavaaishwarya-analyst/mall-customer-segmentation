# mall-customer-segmentation
K-Means Clustering project to segment retail mall customers by age, income, and spending behavior

## Overview
Used unsupervised machine learning to segment 200 retail mall customers 
into 5 distinct groups based on age, annual income, and spending behavior.

## Tools Used
- Python, Pandas, NumPy
- Scikit-Learn (KMeans, StandardScaler, PCA, silhouette_score)
- Matplotlib

## Key Steps
1. Loaded and explored the dataset, scaled features with StandardScaler
2. Used the Elbow Method to identify optimal k
3. Validated with Silhouette Scores — both agreed on k=5
4. Visualized clusters using 2D scatter plot and PCA projection

## Results — 5 Customer Segments Found
| Cluster | Profile | Business Action |
|---------|---------|----------------|
| 0 | Older, low income, low spenders | Budget promotions |
| 1 | Young, moderate income, high spenders | Trend-driven campaigns |
| 2 | Mid-age, high income, high spenders ⭐ | VIP loyalty program |
| 3 | Mid-age, high income, low spenders 🎯 | Re-engagement offers |
| 4 | Older, mid income, average spenders | Seasonal deals |
