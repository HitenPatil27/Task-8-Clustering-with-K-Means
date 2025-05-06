# Task 8 - Customer Segmentation Using K-Means Clustering

This project was completed as part of the AI & ML Internship Task 8. The goal is to perform customer segmentation using K-Means clustering on the **Online Retail Dataset**.

---

## 🧠 Objective

Learn how to:
- Perform data cleaning and preprocessing
- Engineer RFM (Recency, Frequency, Monetary) features
- Normalize the data
- Apply K-Means clustering
- Evaluate clusters using the Elbow Method and Silhouette Score
- Visualize customer segments

---

## 📁 Dataset

We used the [Online Retail Dataset](https://www.kaggle.com/datasets/yasserh/customer-segmentation-dataset).

---

## 🧰 Tools & Libraries

- **Python**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib & Seaborn** for visualizations
- **Scikit-learn** for scaling, clustering, and metrics

---

## 🔍 Steps Performed

### 1. Data Loading
- Loaded `Online Retail.xlsx` into a pandas DataFrame.

### 2. Data Cleaning
- Removed rows with missing values.
- Filtered only positive `Quantity` and `UnitPrice`.
- Filtered data for customers in the United Kingdom.

### 3. RFM Feature Engineering
- **Recency**: Days since the last purchase.
- **Frequency**: Number of unique invoices.
- **Monetary**: Total spending (Quantity × Unit Price).

### 4. Data Normalization
- Scaled `Recency`, `Frequency`, and `Monetary` using `StandardScaler`.

### 5. K-Means Clustering
- Used the **Elbow Method** to determine optimal number of clusters.
- Applied KMeans with selected `k`.
- Calculated **Silhouette Score** for cluster evaluation.

### 6. Visualization
- Used `pairplot` to visualize customer segments by cluster.

---

## 📊 Visualizations Included

- Elbow curve for choosing `k`
- Silhouette score printout
- Pair plots of RFM features by cluster

---

## ✅ Final Outcome

A segmented customer base using K-Means clustering, ready for further analysis or targeted marketing strategies.

