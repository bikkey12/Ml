#  SmartCart Customer Segmentation using K-Means Clustering

##  Project Overview

SmartCart is an online retail company that collected extensive customer data consisting of **2240 customer records and 22 attributes**, including demographics, purchase behavior, website activity, and customer feedback.

Currently, SmartCart uses generic marketing strategies for all customers without understanding different customer behavior patterns. This leads to:

* Inefficient marketing campaigns
* Missed opportunities to retain high-value customers
* Delayed identification of churn-prone users

This project aims to build an intelligent customer segmentation system using **unsupervised machine learning** to discover hidden patterns and support personalized marketing and customer retention.

---

#  Business Objective

The objective of this project is to group customers into meaningful segments based on:

* Purchasing behavior
* Website activity
* Engagement levels
* Loyalty indicators

These segments help businesses make data-driven decisions and improve customer retention.

---

#  Dataset Information

* **Total Records:** 2240 customers
* **Total Features:** 22 attributes

### Customer Demographics

* Year_Birth
* Education
* Marital_Status
* Income
* Kidhome
* Teenhome
* Dt_Customer

### Spending Behaviour

* MntWines
* MntFruits
* MntMeatProducts
* MntFishProducts
* MntSweetProducts
* MntGoldProds

### Purchase Behaviour

* NumDealsPurchases
* NumWebPurchases
* NumCatalogPurchases
* NumStorePurchases
* NumWebVisitsMonth

### Customer Feedback

* Recency
* Complain

---

#  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Principal Component Analysis (PCA)
* K-Means Clustering

---

#  Project Workflow

## 1. Data Cleaning

* Handled missing values
* Removed duplicates
* Treated outliers

## 2. Feature Engineering

Created additional features:

* Total_Spending
* Customer_Tenure_Days
* Total_Children
* Living_With

## 3. Data Preprocessing

* Label Encoding
* Feature Scaling using StandardScaler

## 4. Dimensionality Reduction

Applied PCA for cluster visualization.

## 5. Customer Segmentation

Implemented K-Means Clustering and used:

* Elbow Method
* Silhouette Score

The optimal number of clusters was selected and customers were segmented into four groups.

---

#  Visualizations

The project includes:

* Correlation Heatmap
* Elbow Method Plot
* PCA Scatter Plot
* Cluster Distribution
* Cluster-wise Analysis

---

#  Results

Successfully segmented customers into **4 distinct clusters** based on purchasing behavior and demographics.

The segmented customer dataset was exported as:

```text
Customer_Segmentation_Output.csv
```

---

#  Business Impact

Customer segmentation enables SmartCart to:

✅ Identify high-value customers

✅ Design personalized marketing campaigns

✅ Improve customer retention

✅ Increase customer engagement

✅ Support data-driven decision making

---

#  Project Structure

```
SmartCart-Customer-Segmentation
│
├── smartCart.ipynb
├── Customer_Segmentation_Output.csv
├── README.md
├── requirements.txt
└── images/
```

---

#  Machine Learning Techniques Used

* Unsupervised Learning
* K-Means Clustering
* Principal Component Analysis (PCA)
* Feature Engineering
* Data Visualization

---

# 🚀 Future Improvements

* Deploy the project 
* Save trained models using Joblib
* Build an interactive dashboard
* Add real-time customer segment prediction

---

# 👨 Author

**Bikkey Kumar**

### Skills Demonstrated

* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis
* Data Visualization
* Unsupervised Machine Learning
* Customer Segmentation
* Business Insight Generation
