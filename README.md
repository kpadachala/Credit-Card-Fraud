# Credit Card Fraud Detection & Customer Segmentation

## 📌 Project Overview

A complete end-to-end **data analytics and machine learning project** performed on a large-scale credit card transaction dataset containing over **568,000 records**. The project applies both **classification and clustering techniques** to detect fraudulent transactions and uncover hidden transaction behavior patterns.

---

## 🎯 Problem Statements

1. Predict whether a credit card transaction is fraudulent based on transaction features.
2. Compare multiple classification algorithms to identify the best-performing fraud detection model.
3. Segment transactions into distinct behavioral clusters using unsupervised learning techniques.

---

## 📊 Dataset Description

* **Rows:** 568,630 transactions
* **Columns:** 31
* **Features:** PCA-transformed variables (V1–V28), transaction amount
* **Target:** `Class` (0 = Normal, 1 = Fraud)
* **Data Quality:** No missing values, fully numerical

---

## 🧠 Approach

1. Data loading and validation
2. Exploratory Data Analysis (EDA)
3. Feature scaling and preprocessing
4. Classification using multiple ML models
5. Clustering using unsupervised algorithms
6. Performance evaluation and result interpretation

---

## 📈 Exploratory Data Analysis

* Fraud vs Non-Fraud distribution analysis
* Transaction amount distribution visualization
* PCA-based dimensionality reduction for clustering visualization

---

## 🤖 Machine Learning Techniques Used

### Classification

* Logistic Regression (baseline, interpretable)
* Decision Tree Classifier (non-linear modeling)
* Random Forest Classifier (ensemble, high accuracy)

### Clustering

* K-Means Clustering
* DBSCAN (applied on sampled data due to computational constraints)
* Hierarchical Clustering (conceptual analysis)

---

## 📌 Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cluster visualization using PCA

---

## ⚠️ Assumptions

* PCA features preserve transaction behavior patterns
* Transactions are independent
* Sampling is sufficient for unsupervised clustering on large datasets

---

## 🛠 Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook
