# 🚀 End-to-End Machine Learning Pipeline with Unsupervised + Supervised Learning

## 📌 Project Overview

This project presents a complete **end-to-end machine learning pipeline** that integrates both **unsupervised learning** and **supervised learning** techniques to enhance predictive performance.

The core idea is to extract **hidden patterns, clusters, and anomalies** from data using unsupervised models and use these insights as **feature engineering inputs** for supervised models.

---

## 🎯 Objectives

* Identify hidden patterns in large datasets
* Improve prediction accuracy using advanced feature engineering
* Combine clustering, anomaly detection, and probabilistic modeling
* Build a production-ready ML pipeline

---

## 🧠 Models Used

### 🔹 Unsupervised Learning

* K-Means Clustering → Pattern grouping
* DBSCAN → Outlier detection
* Gaussian Mixture Model (GMM) → Probabilistic clustering
* Hierarchical Clustering → Data relationship analysis

### 🔹 Supervised Learning

* Linear Regression
* Decision Tree
* XGBoost (Final Model)

---

## ⚙️ Pipeline Architecture

1. Data Preprocessing

   * Handling missing values
   * Feature scaling using StandardScaler

2. Unsupervised Learning

   * Cluster generation (K-Means)
   * Outlier detection (DBSCAN)
   * Probabilistic features (GMM)

3. Feature Engineering

   * Cluster labels
   * Outlier flags
   * Probability features

4. Supervised Learning

   * Model training (XGBoost and others)
   * Model evaluation

---

## 🔥 Key Innovation

Instead of relying only on raw data, this project introduces a **hybrid learning approach**:

* Extract hidden structure using unsupervised learning
* Feed these insights into supervised models
* Improve prediction capability

---

## 📊 Features Added to Model

* `kmeans_cluster`
* `dbscan_outlier`
* `gmm_cluster`
* `gmm_probabilities`

---

## 📈 Model Evaluation

* Accuracy Score
* Classification Report
* Feature Importance Analysis

---

## 💾 Model Saving

All models and preprocessing steps are saved as a unified pipeline using `joblib`:

* Scaler
* Clustering models
* Classification models

---

## 🚀 Future Scope

* Deploy as API (FastAPI / Flask)
* Build frontend dashboard
* Real-time prediction system
* Model optimization & tuning

---

## 💡 Real-World Applications

* Fraud Detection
* Customer Segmentation
* User Behavior Analysis
* Risk Prediction Systems

---

## 🧾 Conclusion

This project demonstrates how combining **unsupervised and supervised learning** can significantly enhance model performance and provide deeper insights into data.

---

## 👩‍💻 Author

Puja Midde
Computer Science Engineering Student

---
