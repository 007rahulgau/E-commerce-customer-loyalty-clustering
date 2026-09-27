# Customer Loyalty & Repeat Purchase Clustering

## 📌 Project Overview
This project applies **KMeans clustering** to customer loyalty and repeat purchase data.  
The goal is to identify meaningful customer segments that highlight differences in **loyalty tier** (Bronze, Silver, Gold, Platinum) and **repeat purchase behavior (Y/N)**.

## 🎯 Objectives
- Segment customers into clusters based on purchase and loyalty features.
- Analyze how clusters align with **loyalty tiers** and **repeat purchase flags**.
- Validate cluster significance using **Chi‑square contingency tests**.
- Provide actionable insights for customer retention and loyalty programs.

## 🛠 Methods Used
- **Data preprocessing**: scaling numeric features, encoding categorical variables.
- **KMeans clustering**: selecting optimal `k` using the elbow method.
- **Cluster profiling**: centroids, crosstabs, normalized percentages.
- **Statistical validation**: Chi‑square tests for independence.
- **Visualization**: bar charts, heatmaps, and distribution plots.

## 📊 Key Insights
- **Cluster 2** → Majority repeat buyers across all tiers (loyalist group).  
- **Cluster 1** → Over‑represented with one‑time buyers (churn‑risk group).  
- **Cluster 0** → Balanced mix of repeaters and non‑repeaters, stronger presence in Gold/Silver tiers.  
- Chi‑square tests confirm clusters are **significantly associated** with both loyalty tier (p ≈ 0.025) and repeat purchase behavior (p ≈ 6.9e‑14).

## 📂 Repository Structure
