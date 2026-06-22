#  Classification Algorithms on the Iris Dataset

## Overview

This project explores and compares three fundamental machine learning classification algorithms using the Iris dataset:

* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Gaussian Naive Bayes

The project also investigates the effect of dimensionality reduction using Principal Component Analysis (PCA) and compares model performance before and after feature reduction.

---

## Objective

The goal of this project is to understand how different classification algorithms perform on the same dataset and to study the impact of preprocessing techniques such as feature scaling and dimensionality reduction.

---

## Dataset Information

**Dataset:** Iris Dataset

| Metric         | Value |
| -------------- | ----- |
| Total Samples  | 150   |
| Features       | 4     |
| Classes        | 3     |
| Missing Values | 0     |

Classes:

* Setosa
* Versicolor
* Virginica

---

## Exploratory Data Analysis

The dataset was inspected to:

* Understand feature distributions
* Verify class balance
* Check for missing values
* Visualize relationships between features using pair plots

Key Findings:

* No missing values were present.
* All three classes were equally distributed.
* Several features showed strong class separation.

---

## Data Preprocessing

The following preprocessing techniques were applied:

* Train-Test Split
* Standard Scaling (for KNN)
* Min-Max Scaling (for SVM and Naive Bayes)
* Label Encoding
* Principal Component Analysis (PCA)

---

## Models Implemented

### 1. K-Nearest Neighbors (KNN)

Multiple values of K were tested to evaluate model stability.

| K Value | Accuracy |
| ------- | -------- |
| 1       | 1.00     |
| 3       | 1.00     |
| 5       | 1.00     |
| 7       | 1.00     |
| 9       | 1.00     |

---

### 2. Support Vector Machine (SVM)

Different kernel functions were compared.

| Kernel     | Accuracy |
| ---------- | -------- |
| Linear     | 1.00     |
| RBF        | 1.00     |
| Polynomial | 0.9333   |

---

### 3. Gaussian Naive Bayes

| Model                | Accuracy |
| -------------------- | -------- |
| Original Features    | 1.00     |
| PCA Reduced Features | 0.9667   |

---

## PCA Analysis

Principal Component Analysis (PCA) was used to reduce dimensionality while retaining 95% of the dataset variance.

| Metric            | Value |
| ----------------- | ----- |
| Original Features | 4     |
| PCA Features      | 2     |

Results showed that dimensionality reduction slightly reduced classification accuracy while significantly decreasing feature space complexity.

---

## Key Learnings

* Importance of feature scaling for distance-based algorithms.
* Comparison between distance-based, margin-based, and probabilistic classifiers.
* Understanding of SVM kernel functions.
* Application of dimensionality reduction using PCA.
* Trade-offs between model simplicity and predictive performance.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Results Summary

| Algorithm                  | Best Accuracy |
| -------------------------- | ------------- |
| KNN                        | 1.00          |
| SVM                        | 1.00          |
| Gaussian Naive Bayes       | 1.00          |
| Gaussian Naive Bayes + PCA | 0.9667        |

The Iris dataset is highly structured and well-separated, resulting in excellent classification performance across multiple machine learning algorithms.

---

## Author

**Pragya Pal**
