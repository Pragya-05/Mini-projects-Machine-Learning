# Loan Approval Prediction using Machine Learning

## Project Overview

This project focuses on predicting loan approval status using machine learning techniques. The workflow includes data exploration, preprocessing, feature engineering, model training, and evaluation.

The objective is to build a reliable classification model that can determine whether a loan application is likely to be approved based on an applicant's financial and demographic information.

---

## Dataset Information

The dataset contains 4,269 loan applications and includes information such as:

* Loan ID
* Number of Dependents
* Education
* Self Employment Status
* Annual Income
* Loan Amount
* Loan Term
* CIBIL Score
* Residential Asset Value
* Commercial Asset Value
* Luxury Asset Value
* Bank Asset Value
* Loan Status

---

## Project Workflow

### Part 1: Exploratory Data Analysis (EDA)

* Loaded and inspected the dataset
* Examined dataset shape and feature names
* Identified data types
* Checked for missing values
* Generated summary statistics
* Explored feature distributions and relationships

### Part 2: Data Preprocessing

* Handled missing values using appropriate imputation techniques
* Encoded categorical variables using Label Encoding
* Scaled numerical features using MinMaxScaler
* Prepared feature matrix and target variable
* Split data into training and testing datasets

### Part 3: Model Training and Evaluation

* Trained a Logistic Regression classifier
* Evaluated model performance on unseen data
* Generated confusion matrix and classification report
* Built a reusable prediction function
* Saved the trained model using Joblib

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Joblib
* Jupyter Notebook

---

## Model Performance

The Logistic Regression model achieved strong classification performance on the test dataset.

Evaluation metrics included:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score

---

## Project Structure

loan_data_exploration/

├── loan_analysis.ipynb

├── loan_approval.csv

├── loan_approval_model.pkl

└── README.md

---

## Future Improvements

* Compare multiple machine learning algorithms
* Perform feature selection and engineering
* Deploy the model using Streamlit or Flask
* Build a web interface for real-time loan prediction

---

## Conclusion

This project demonstrates a complete machine learning workflow, starting from raw data exploration and preprocessing to model training, evaluation, and model persistence. The resulting model can be used as a foundation for automated loan approval prediction systems.
