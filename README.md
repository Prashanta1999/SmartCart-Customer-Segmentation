# SmartCart Customer Segmentation System

## Overview

The **SmartCart Customer Segmentation System** is an Unsupervised Machine Learning project designed to analyze customer purchasing behavior and group customers into meaningful segments. The goal is to help SmartCart improve marketing effectiveness, customer engagement, and retention strategies through data-driven decision-making.

By leveraging clustering algorithms, the system identifies hidden patterns in customer demographics, spending habits, website activity, and loyalty indicators.

---

## Problem Statement

SmartCart is a growing e-commerce platform serving customers across multiple countries. The company has collected customer data containing 2,240 customer records and 22 attributes, including demographics, purchase behavior, website activity, and customer feedback.

Currently, SmartCart applies generic marketing campaigns to all customers without understanding different customer behavior patterns. This results in:

* Inefficient marketing campaigns
* Poor customer targeting
* Missed opportunities to retain high-value customers
* Delayed identification of churn-prone customers

To address these challenges, this project builds an intelligent customer segmentation system using unsupervised machine learning techniques.

---

## Objectives

* Analyze customer purchasing behavior and engagement patterns
* Discover hidden customer segments using clustering algorithms
* Identify high-value and loyal customers
* Detect low-engagement and potential churn customers
* Support personalized marketing campaigns
* Enable data-driven business decisions

---

## Dataset Description

The dataset contains customer demographic information, spending behavior, purchase frequency, and customer activity metrics.

### Customer Demographics

| Feature        | Description                      |
| -------------- | -------------------------------- |
| ID             | Unique customer identifier       |
| Year_Birth     | Year of birth                    |
| Education      | Highest education level          |
| Marital_Status | Marital status                   |
| Income         | Annual household income          |
| Kidhome        | Number of children in household  |
| Teenhome       | Number of teenagers in household |
| Dt_Customer    | Date of customer enrollment      |

### Purchase Behavior (Amount Spent)

| Feature          | Description                   |
| ---------------- | ----------------------------- |
| MntWines         | Amount spent on wines         |
| MntFruits        | Amount spent on fruits        |
| MntMeatProducts  | Amount spent on meat products |
| MntFishProducts  | Amount spent on fish products |
| MntSweetProducts | Amount spent on sweets        |
| MntGoldProds     | Amount spent on gold products |

### Purchase Behavior (Frequency)

| Feature             | Description                    |
| ------------------- | ------------------------------ |
| NumDealsPurchases   | Purchases made using discounts |
| NumWebPurchases     | Website purchases              |
| NumCatalogPurchases | Catalog purchases              |
| NumStorePurchases   | In-store purchases             |
| NumWebVisitsMonth   | Monthly website visits         |

### Customer Activity & Feedback

| Feature  | Description                                    |
| -------- | ---------------------------------------------- |
| Recency  | Days since last purchase                       |
| Complain | Customer complaint indicator (1 = Yes, 0 = No) |

---

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Feature Scaling
6. Dimensionality Reduction using PCA
7. Customer Segmentation using Clustering Algorithms
   - K-Means Clustering
   - Agglomerative (Hierarchical) Clustering
8. Cluster Evaluation and Visualization
9. Business Insights Generation

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* PCA (Principal Component Analysis)
* K-Means Clustering
* Agglomerative Hierarchical Clustering

---

## Expected Outcomes

The system will identify distinct customer groups such as:

* High-Value Customers
* Loyal Customers
* Frequent Buyers
* Discount-Oriented Customers
* Low Engagement Customers
* Potential Churn Customers

These insights can help SmartCart create targeted marketing campaigns and improve customer retention.

---

## Project Structure

```text
SmartCart-Clustering-System/
│
├── smartcart_clustering.ipynb
├── README.md
└── .gitignore

```

## Author

**Prashanta Chowdhury**  
Aspiring AI/ML Engineer | Data Science Enthusiast  