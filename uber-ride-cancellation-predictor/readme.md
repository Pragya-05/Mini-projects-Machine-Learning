# Uber Ride Cancellation Predictor

## Overview

This project builds a machine learning model to predict whether an Uber ride booking will be cancelled before the ride begins.

The project follows a complete machine learning workflow, including exploratory data analysis, data preprocessing, feature engineering, model training, and evaluation.

---

## Dataset

The dataset contains ride booking information such as:

* Vehicle Type
* Pickup Location
* Drop Location
* Average Vehicle Time to Arrival (VTAT)
* Average Customer Time to Arrival (CTAT)
* Payment Method
* Booking Status

---

## Project Structure

### Part 1: Exploratory Data Analysis (EDA)

* Loaded and explored the dataset
* Calculated cancellation rate
* Identified peak cancellation hours
* Analyzed customer and driver cancellation reasons
* Visualized cancellation patterns

### Part 2: Data Cleaning and Preprocessing

* Created the target variable (`is_cancelled`)
* Removed irrelevant ride statuses
* Handled missing values
* Engineered time-based features
* Removed data leakage and unnecessary columns
* Generated a clean modeling dataset

### Part 3: Machine Learning Model

* Applied One-Hot Encoding to categorical variables
* Split data into training and testing sets
* Trained a Decision Tree Classifier
* Evaluated model performance
* Generated prediction examples
* Compared performance with a Random Forest model

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## Key Skills Demonstrated

* Data Analysis
* Feature Engineering
* Data Preprocessing
* Classification Modeling
* Model Evaluation
* Data Visualization

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Advanced ensemble models
* Deployment as a web application
