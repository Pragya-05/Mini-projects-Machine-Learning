# Language Detection System

## Overview

The Language Detection System is a Natural Language Processing (NLP) project that automatically identifies the language of a given text input. The project uses machine learning techniques to classify text into one of 17 supported languages.

The workflow includes data exploration, text preprocessing, feature extraction using TF-IDF, and language classification using the Multinomial Naive Bayes algorithm.

---

## Dataset

* Dataset: Language Detection Dataset
* Total Samples: 10,337
* Total Languages: 17

Supported Languages:

* English
* French
* Spanish
* Portuguese
* Italian
* Russian
* Swedish
* Malayalam
* Dutch
* Arabic
* Turkish
* German
* Tamil
* Danish
* Kannada
* Greek
* Hindi

---

## Project Workflow

### Part 1: Exploratory Data Analysis (EDA)

* Loaded and inspected the dataset
* Checked for missing values
* Checked for empty text entries
* Analyzed language distribution
* Examined text lengths
* Checked duplicate records

### Part 2: Data Cleaning & Preprocessing

The text preprocessing pipeline performs:

* Conversion to lowercase
* Removal of punctuation
* Removal of numbers
* Removal of special characters
* Removal of extra whitespace

The cleaned dataset is saved as:

Language_Detection_Cleaned.csv

### Part 3: Model Building

* Train-Test Split (80-20)
* TF-IDF Vectorization
* Multinomial Naive Bayes Classifier
* Model Evaluation using Accuracy, Precision, Recall, and F1 Score
* Model Serialization using Joblib

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Joblib
* Regular Expressions (re)

---

## Model Performance

### Accuracy

95.79%

### Classification Metrics

* Weighted F1 Score: 0.96
* Strong performance across most languages
* Excellent classification results for Arabic, French, Italian, Russian, Spanish, Tamil, Malayalam, and Dutch

---

## Project Structure

Language_Detection_System/

├── Language Detection.csv

├── Language_Detection_Cleaned.csv

├── language_detection_model.joblib

├── main.ipynb

└── README.md

---

## Example Predictions

Input:
"This is a language detection test."

Prediction:
English

Input:
"Bonjour comment allez vous"

Prediction:
French

Input:
"Hola como estas"

Prediction:
Spanish

Input:
"Это тест системы определения языка"

Prediction:
Russian

---

## Future Improvements

* Support additional languages
* Deploy as a web application using Flask or Streamlit
* Compare multiple machine learning algorithms
* Explore deep learning approaches such as LSTM and Transformers
* Improve performance on low-sample languages such as Hindi

---

## Author

Pragya Pal

Machine Learning & Data Science Projects Portfolio
