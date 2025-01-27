# Overview
This repository contains the solution for an eCommerce transaction dataset assignment. The primary goal is to perform data analysis, build predictive models, and segment customers effectively to extract actionable insights for business strategies.

The dataset consists of three files:
1. Customers.csv - Contains customer profiles.
2. Products.csv - Contains product details.
3. Transactions.csv - Contains transaction records.

# Tasks Performed and Deliverables

# 1. Exploratory Data Analysis (EDA) and Business Insights

Conducted an in-depth EDA to explore customer behaviors, product preferences, and transaction patterns.
Generated key business insights:<br>
-> Identified top-selling products and customer regions.<br>
-> Analyzed seasonal purchasing trends.<br>
-> Determined customer lifetime value metrics.<br>

# 2. Lookalike Model

-> Developed a recommendation model to find similar customers based on profiles and transaction history.<br>
-> Recommendations are ranked with a similarity score.<br>
-> Output includes the top 3 similar customers for the first 20 customers (C0001 to C0020).

# 3. Customer Segmentation
-> Used clustering algorithms (K-Means and Hierarchical Clustering) to segment customers into distinct groups based on their profiles and transaction behaviors.<br>
-> Evaluated clusters using metrics such as:<br>
        Davies-Bouldin Index<br>
        Silhouette Score<br>
-> Visualized clustering results with dendrograms and PCA plots.

# Key Results
Hierarchical Clustering:<br>
  Number of Clusters: 10<br>
  Davies-Bouldin Index: 0.9997<br>
  Silhouette Score: 0.3125<br>
K-Means Clustering:<br>
  Number of Clusters: 10<br>
  Davies-Bouldin Index: 1.0459<br>
  Inertia: 12.3782<br>
  Silhouette Score: 0.2874

