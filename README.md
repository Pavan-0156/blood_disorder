# blood_disorder
# 🩸 Blood Donation Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict whether a blood donor is likely to donate blood in the future based on their donation history. Using a supervised classification approach, we help healthcare facilities and blood banks identify potential recurring donors to maintain a steady blood supply.

## 📊 Dataset Description

The dataset is sourced from the [Blood Transfusion Service Center Data Set](https://archive.ics.uci.edu/ml/datasets/Blood+Transfusion+Service+Center) on the UCI Machine Learning Repository.

### 🔗 Dataset Link:
[UCI Blood Donation Dataset](https://archive.ics.uci.edu/ml/datasets/Blood+Transfusion+Service+Center)

### 📁 Features:

| Feature | Description |
|--------|-------------|
| `Recency` | Months since the last donation |
| `Frequency` | Total number of donations |
| `Monetary` | Total blood donated (in c.c.) |
| `Time` | Months since the first donation |
| `Target` | 1 if the donor donated in March 2007, 0 otherwise |

## 💻 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 🔍 Problem Statement

Given the donation history of individuals, the goal is to **predict whether they will donate blood in the future**, helping organizations improve donor engagement and campaign targeting.

## ⚙️ ML Models Used

- Logistic Regression
- Random Forest Classifier
- K-Nearest Neighbors
- Support Vector Machine (SVM)

## 📈 Evaluation Metrics

- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve

## ✅ Results Summary

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| ~76%     |
| Random Forest      | ~78%     |
| KNN                | ~75%     |
| SVM                | ~77%     |

> 🔍 Random Forest provided the best overall performance.

## 📌 Visualizations

- Donation trends
- Model performance metrics
- Correlation heatmap
- ROC-AUC curves






