# Student Dropout Risk Analysis

## Overview

This project uses machine learning techniques to identify students who are at risk of dropping out based on academic, demographic, and financial information.

The goal is to help educational institutions detect at-risk students early and enable timely interventions.

---

## Dataset

The dataset contains information about:

* Demographic factors
* Academic performance
* Financial status
* Enrollment details

Total Records: 4424

Target Classes:

* Dropout
* Graduate
* Enrolled

---

## Project Workflow

### Part 1: Data Exploration and Feature Engineering

* Loaded dataset using Pandas
* Explored data structure and distributions
* Checked missing values
* Created engineered features:

  * approval_rate
  * performance_score

### Part 2: Model Training and Regularization

Implemented:

* Decision Tree Classifier
* Logistic Regression
* L1 Regularization (Lasso)
* L2 Regularization (Ridge)

Evaluation Metrics:

* Accuracy
* Confusion Matrix
* Classification Report

### Part 3: Ensemble Learning

Implemented:

* Random Forest Classifier
* Gradient Boosting Classifier
* K-Fold Cross Validation

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* Confusion Matrix
* Cross Validation Score

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* Git
* GitHub

---

## Project Structure

student-dropout-risk-analysis/

├── data/

├── notebooks/

│ ├── part1_data_exploration.ipynb

│ ├── part2_model_training.ipynb

│ └── part3_ensemble_methods.ipynb

└── README.md

---

## Future Improvements

* Hyperparameter tuning
* Feature importance analysis
* Model deployment using Flask/Streamlit
* Interactive dashboard for student risk monitoring
