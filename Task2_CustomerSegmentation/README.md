# Task 2 - Customer Segmentation Analysis

## Objective
Segment an e-commerce company's customers into distinct groups based on purchasing behaviour using K-Means clustering, to enable targeted marketing.

## Tools Used
Python, pandas, scikit-learn (KMeans, StandardScaler), matplotlib, seaborn, Jupyter Notebook

## Dataset
Online Retail Dataset (UCI/Kaggle) - transactional data cleaned to 397,884 rows, aggregated into 4,338 unique customers.

## Method
1. Cleaned data: removed missing CustomerIDs and invalid transactions
2. Built RFM features (Recency, Frequency, Monetary) per customer
3. Scaled features using StandardScaler
4. Used the Elbow Method to find optimal K (K=4)
5. Applied K-Means clustering and profiled each segment

## Key Findings
- Cluster 0 (3,054 customers): Regular, active customers
- Cluster 1 (1,067 customers): Lapsed/at-risk customers
- Cluster 2 (13 customers): VIP customers, extremely high value
- Cluster 3 (204 customers): Loyal, high-value customers

## How to Run
1. Clone this repo
2. Open `ImnahIfthikar_Task2.ipynb` in Jupyter Notebook
3. Ensure the Online Retail CSV is in the same folder
4. Run all cells
