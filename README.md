# Customer Segmentation Analysis using K-Means Clustering

## Project Overview

This project applies **Customer Segmentation** techniques to an e-commerce dataset using **RFM (Recency, Frequency, Monetary) Analysis** and the **K-Means Clustering** algorithm. The objective is to group customers based on their purchasing behaviour to help businesses implement targeted marketing strategies.

This project was completed as part of the **Oasis Infobyte Data Analytics Internship (Level 1 – Task 2).**

---

## Objective

To segment customers into distinct groups based on purchasing behaviour using Machine Learning (K-Means Clustering) and provide actionable marketing recommendations for each customer segment.

---

## Dataset

- **Dataset:** Online Retail Dataset
- **Source:** UCI Machine Learning Repository / Kaggle
- **Records:** 541,909 transactions
- **Features:** 8 columns

Main columns include:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code
- Git & GitHub

---

## Project Workflow

### 1. Data Loading
- Imported the Online Retail dataset
- Inspected dataset structure
- Checked data types and missing values

### 2. Data Cleaning
- Removed missing Customer IDs
- Removed missing product descriptions
- Converted InvoiceDate to datetime
- Converted CustomerID to integer

### 3. Feature Engineering
Created RFM (Recency, Frequency, Monetary) features:

- Recency
- Frequency
- Monetary

### 4. Data Standardization
- Applied StandardScaler before clustering

### 5. K-Means Clustering
- Used the Elbow Method to determine the optimal number of clusters
- Applied K-Means with K = 3

### 6. Data Visualization
Created:
- Elbow Method Plot
- Recency vs Monetary Scatter Plot
- Frequency vs Monetary Scatter Plot
- Customer Count by Cluster Bar Chart

### 7. Cluster Profiling
Calculated average:
- Recency
- Frequency
- Monetary

for each customer cluster.

---

## Customer Segments

### Cluster 0 – Regular Customers
- Moderate spending
- Moderate purchase frequency
- Recent purchases

**Recommendation**
- Loyalty rewards
- Product recommendations
- Promotional offers

---

### Cluster 1 – Inactive Customers
- Low spending
- Low purchase frequency
- Long time since last purchase

**Recommendation**
- Re-engagement campaigns
- Discount coupons
- Personalized email marketing

---

### Cluster 2 – VIP Customers
- Highest spending
- Highest purchase frequency
- Most recent purchases

**Recommendation**
- VIP membership
- Exclusive offers
- Early access to new products
- Premium customer support

---

## Business Insights

The K-Means model successfully identified three distinct customer groups with different purchasing behaviours. These insights can help businesses:

- Improve customer retention
- Increase customer lifetime value
- Design targeted marketing campaigns
- Reward high-value customers
- Re-engage inactive customers

---

## Project Structure

```
Customer-Segmentation-KMeans/
│
├── Customer_Segmentation.ipynb
├── OnlineRetail.csv
├── README.md
├── .gitignore
```

---

## Author

**Angela Iseriehen**

GitHub: https://github.com/Osas-25

OASIS Infobyte Data Analytics Internship – Level 1 Task 2
