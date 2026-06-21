# 🎬 Movie Review Sentiment Analyzer

## Overview

The Movie Review Sentiment Analyzer is a Natural Language Processing (NLP) project that automatically classifies movie reviews as **Positive** or **Negative**.

Using the IMDB Movie Reviews Dataset, the project applies text preprocessing techniques, TF-IDF feature extraction, and machine learning algorithms to analyze sentiment from user-generated reviews.

---

## Objective

The objective of this project is to develop a machine learning model capable of understanding textual review data and accurately predicting the sentiment expressed within a review.

---

## Dataset

**Dataset:** IMDB Movie Reviews Dataset

| Metric | Value |
|----------|----------|
| Total Reviews | 50,000 |
| Positive Reviews | 25,000 |
| Negative Reviews | 25,000 |
| Missing Values | 0 |

The dataset is perfectly balanced, making it suitable for binary sentiment classification.

---

## Exploratory Data Analysis

Key findings from the initial analysis:

- Dataset contains 50,000 labeled movie reviews.
- No missing values were found.
- Positive and negative classes are equally distributed.
- Average review length is approximately 231 words.
- Positive reviews are slightly longer on average than negative reviews.

---

## Data Preprocessing Pipeline

The following NLP preprocessing steps were applied:

- HTML Tag Removal
- Lowercase Conversion
- Punctuation Removal
- Stopword Removal
- Word Stemming using Porter Stemmer
- TF-IDF Feature Extraction

After preprocessing, textual reviews were transformed into a numerical feature matrix using TF-IDF vectorization with 5,000 features.

---

## Machine Learning Models

### Logistic Regression

| Metric | Score |
|----------|----------|
| Accuracy | 88.57% |
| Precision | 89% |
| Recall | 89% |
| F1 Score | 89% |

### Multinomial Naive Bayes

| Metric | Score |
|----------|----------|
| Accuracy | 84.83% |

---

## Model Comparison

| Model | Accuracy |
|----------|----------|
| Logistic Regression | **88.57%** |
| Multinomial Naive Bayes | 84.83% |

**Best Performing Model:** Logistic Regression

---

## Project Workflow

```text
Data Collection
        ↓
Exploratory Data Analysis
        ↓
Text Preprocessing
        ↓
TF-IDF Vectorization
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Sentiment Prediction
```

---

## Sample Predictions

### Example 1

**Input Review**

> This movie was absolutely fantastic and I loved every moment.

**Prediction**

```text
Positive
```

### Example 2

**Input Review**

> This was one of the worst movies I have ever seen.

**Prediction**

```text
Negative
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

---

## Future Improvements

- Hyperparameter Optimization
- Deep Learning-based Sentiment Analysis
- BERT Transformer Implementation
- Streamlit Web Application Deployment
- Real-time Review Classification

---

## Results

The final Logistic Regression model achieved an accuracy of **88.57%**, demonstrating strong performance in classifying movie review sentiment using traditional NLP techniques and TF-IDF feature engineering.

---

