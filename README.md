# Model Training: Regression and Classification 🚀

This repository showcases my practical experience with foundational machine learning algorithms. It contains two distinct projects demonstrating both regression and classification techniques, alongside model optimization and comparative analysis.

---

## 1. House Price Prediction (Regression)
**Dataset:** `HousePricePrediction`

This project focuses on predicting continuous target variables (house prices) based on various housing features. It demonstrates the complete lifecycle of a regression problem, moving from a baseline model to optimized, penalized models.

* **Baseline Model:** Trained a standard **Linear Regression** model to establish a baseline prediction metric.
* **Model Optimization & Regularization:** To solve issues related to model complexity, overfitting, and underfitting, I implemented two regularization techniques:
  * **Lasso Regression (L1):** Applied L1 regularization to penalize the absolute size of the regression coefficients. This not only helped reduce overfitting but also acted as an automatic feature selector by shrinking less important feature weights to zero.
  * **Ridge Regression (L2):** Applied L2 regularization to penalize the squared magnitude of coefficients. This mitigated multicollinearity and smoothed out the model's predictions, preventing the model from becoming too reliant on any single feature.

---

## 2. Iris Species Classification
**Dataset:** `iris.csv`

This project tackles a classic multi-class classification problem. The objective was to predict the species of an iris flower based on its sepal and petal dimensions. Instead of relying on a single model, I focused on model comparison and evaluation.

* **Algorithms Implemented:**
  * **Logistic Regression:** Served as a strong probabilistic baseline for classification.
  * **K-Nearest Neighbors (KNN):** Implemented a non-parametric, distance-based algorithm to classify data points based on their closest neighbors.
  * **Naive Bayes:** Applied this probabilistic classifier based on Bayes' Theorem, working on the assumption of conditional independence between the flower measurements.
* **Performance Comparison:** Extracted and compared evaluation metrics across all three algorithms. Analyzed the models using classification reports (Accuracy, Precision, Recall, and F1-Score) to determine which algorithm generalized best to the test data.
