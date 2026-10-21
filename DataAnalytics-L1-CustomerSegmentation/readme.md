# Customer Segmentation Analysis (RFM & K-Means)

## Project Overview

This project is part of the Oasis Infobyte Data Analytics Internship (Level 1 - Task 2). The objective is to apply clustering algorithms to segment an e-commerce company's customer base into distinct groups based on purchasing behavior using RFM (Recency, Frequency, Monetary) analysis.

## Tech Stack

- **Language:** Python
- **Libraries:** pandas, numpy, scikit-learn (KMeans, StandardScaler), matplotlib, seaborn
- **Environment:** Jupyter Notebook (VS Code)

## Workflow & Implementation

- **Data Cleaning & Preprocessing:** Handled missing values (dropped missing Customer IDs) and removed cancellations/returns (negative quantities) from the Online Retail dataset.
- **RFM Feature Engineering:**
- **Recency:** Days elapsed since last order relative to the dataset snapshot.
- **Frequency:** Number of unique transactions per customer.
- **Monetary:** Total monetary value spent per customer.
- **Scaling:** Normalized features using `StandardScaler` to prepare for distance-based clustering.
- **Optimal K Selection:** Evaluated inertia across K=1 to 10 using the Elbow Method, identifying K=4 as the optimal cluster count.
- **Clustering & Profiling:** Applied K-Means ($K=4$) to segment customers into VIPs, Loyal High-Spenders, Regular Buyers, and At-Risk groups.
- **Actionable Insights:** Outlined targeted retention and promotional marketing strategies tailored to each segment.
