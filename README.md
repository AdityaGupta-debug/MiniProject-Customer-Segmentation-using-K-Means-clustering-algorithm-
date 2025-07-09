# 🛍️ Customer Segmentation using K-Means Clustering

This mini-project demonstrates customer segmentation using the **K-Means Clustering** algorithm on the Mall Customer Segmentation dataset. The goal is to identify distinct customer groups based on their spending behavior and income levels, which can help businesses target marketing strategies more effectively.

---

## 📂 Dataset Description

**Source:** [Mall Customers Dataset on Kaggle](https://www.kaggle.com/datasets/shwetabh123/mall-customers)

This dataset contains information about customers visiting a mall. It includes demographic data and purchasing behavior.

### 🧾 Features:
- `CustomerID`: Unique ID assigned to each customer
- `Gender`: Gender of the customer (Male/Female)
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income in thousands of dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

---

## 🔍 Project Workflow

### 1. **Data Loading and Preprocessing**
- Loaded the dataset using pandas
- Selected relevant features: `Annual Income` and `Spending Score`
- Plotted the raw data distribution

### 2. **WCC (Within-Cluster Sum of Squares) - Elbow Method**
- Calculated the Within-Cluster Sum of Squares (inertia) for cluster counts ranging from 1 to 10
- Plotted the Elbow Curve to determine the optimal number of clusters

### 3. **K-Means Clustering**
- Based on the Elbow Curve analysis, applied K-Means with the optimal number of clusters (e.g., 5)
- Assigned cluster labels to each customer
- Visualized the resulting customer segments using a scatter plot

---

## 📊 Visualizations Included
- Raw customer distribution (Income vs. Spending Score)
- WCC / Elbow Curve to choose optimal number of clusters
- Final customer clusters with color-coded segmentation

---

## 🧠 Insights
- Customers were successfully grouped into distinct segments
- Each segment shows different income-spending profiles
- This can help in targeted advertising, personalized offers, or loyalty programs

---

## 🛠️ Tools used 
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---
