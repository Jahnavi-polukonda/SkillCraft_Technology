# 🛍️ Mall Customer Segmentation using K-Means Clustering

This project is submitted as **Task 2** of the Machine Learning Internship at **SkillCraft Technology**.  
The goal is to analyze customer data and apply **K-Means Clustering** to identify distinct customer segments based on **Annual Income** and **Spending Score**.

---

## 📁 Dataset Description

A synthetic dataset of 200 mall customers was created with the following attributes:

| Column Name              | Description                              |
|--------------------------|------------------------------------------|
| `CustomerID`             | Unique identifier for each customer      |
| `Gender`                 | Gender of the customer (Male/Female)     |
| `Age`                    | Age of the customer                      |
| `Annual Income (k$)`     | Estimated yearly income in thousands     |
| `Spending Score (1-100)` | Score assigned based on shopping behavior|

📌 **File used**: `mall_customer_dataset.csv`

---

## 🎯 Project Objective

- Understand the relationship between income and spending behavior.
- Apply **K-Means Clustering** to group customers into **5 distinct clusters**.
- Help businesses target their marketing strategies more effectively.

---

## 🧰 Technologies Used

| Tool/Library   | Purpose                     |
|----------------|-----------------------------|
| Python         | Programming Language        |
| Pandas         | Data Manipulation           |
| Matplotlib     | Data Visualization          |
| Seaborn        | Statistical Graphs          |
| scikit-learn   | Machine Learning Algorithms |

---

## 🔍 Steps Performed

### 1️⃣ Data Preprocessing
- Loaded CSV file into a pandas DataFrame.
- Checked for missing values and data types.
- Selected relevant features for clustering.

### 2️⃣ Exploratory Data Analysis
- Plotted gender distribution.
- Analyzed Age vs Spending Score and Income vs Spending Score using scatter plots.

### 3️⃣ Feature Selection
- Selected `Annual Income` and `Spending Score` for clustering.

### 4️⃣ Optimal Clusters – Elbow Method
- Calculated Within-Cluster Sum of Squares (WCSS) for K = 1 to 10.
- Identified **K = 5** as the optimal number of clusters.

### 5️⃣ K-Means Clustering
- Applied `KMeans(n_clusters=5)` to assign cluster labels.
- Added the cluster results to the original dataset.

### 6️⃣ Visualization of Clusters
- Plotted the customer segments with different colors.
- Marked cluster centers using black 'X' markers.

---

## 📊 Output Snapshot

The algorithm successfully segmented customers into 5 clusters based on income and spending behavior.  
Example interpretations:
- Cluster 0: High income, high spenders  
- Cluster 1: Low income, high spenders  
- Cluster 2: Low income, low spenders  
- Cluster 3: High income, low spenders  
- Cluster 4: Average income & average spenders  

