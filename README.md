# Customer Segmentation Project

## Overview
This project analyzes mall customer data and segments them into meaningful groups using *K-Means Clustering. A **Decision Tree Classifier* is then trained to predict customer clusters for new entries. The insights from this project can help businesses design targeted marketing campaigns and personalized offers.

## Features
- Data analysis and visualization using *Pandas, Matplotlib, and Seaborn*
- Customer segmentation using *K-Means Clustering*
- Optimal number of clusters determined with the *Elbow Method*
- Predictive model using *Decision Tree Classifier* (97.5% accuracy)
- Visualized Decision Tree to understand decision rules
- Insights for each cluster to help in marketing strategies

## Data
- Dataset used: Mall_Customers.csv
- Key features:
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)
- Target variable for Decision Tree: Cluster ID (0–4)

## Results
- Customers divided into 5 clusters:
  - *Cluster 0:* Average Income & Average Spending
  - *Cluster 1:* High Income & High Spending
  - *Cluster 2:* High Income & Low Spending
  - *Cluster 3:* Low Income & Low Spending
  - *Cluster 4:* Low Income & High Spending
- Decision Tree can predict new customer clusters based on Age, Income, and Spending Score
- Example: Customer with Age 30, Income 75k, Spending Score 80 → Cluster 1 (Premium customer)

## Future Scope
- Build an *interactive app* to classify new customers instantly
- Automate marketing actions such as sending personalized emails or offers based on predicted clusters.
