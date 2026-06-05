# Linear Regression Mini-Project

This repository contains a mini-project focused on Exploratory Data Analysis (EDA) and Predictive Modeling using a Student Performance dataset. The primary goal is to investigate how strongly a student's **Math Score** correlates with their **Reading Score**, and build a Simple Linear Regression model to predict reading performance.

## 🛠️ Technologies Used
* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## 🚀 Project Overview
* **Objective:** Predict `reading score` based on `math score`.
* **Dataset:** 1,000 student records including demographic data and test scores (Math, Reading, Writing).
* **Algorithm Used:** Simple Linear Regression (`scikit-learn`).

---

## 📊 Key Insights from EDA
* **Distribution Skewness:** Both math and reading scores exhibit a mild **negative skew** (approximately `-0.28` and `-0.26`), meaning that while the majority of students scored on the higher end, a small handful of low-scoring outliers pull the average down.
* **Strong Linear Relationship:** A scatter plot with an ordinary least squares (OLS) trendline reveals a distinct, positive linear relationship between math and reading proficiencies.

---

## ⚙️ Model Setup & Performance

The data was divided into a **70% training** and **30% testing** split (`train_test_split`). 

* **Feature (X):** `math score` (Reshaped to a 2D array for Scikit-Learn compliance)
* **Target (y):** `reading score`

### Results:
* **Model Evaluation:** The Linear Regression model achieved an **$R^2$ score of approximately 0.68**. This indicates that **68% of the variance** in a student's reading score can be explained by their math score alone.

---


