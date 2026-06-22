# Movie_Review_Sentiment_Analysis_Using_TF_IDF_Vectorizer_and_Multinomial_Naive_Bayes

https://colab.research.google.com/drive/1PHQ8XSUmnK3LIqJ1kzoM-veECwWL3uj8#scrollTo=_Za0H8zRfbwS

# 🎬 Movie Review Sentiment Analysis Using TF-IDF Vectorizer and Multinomial Naive Bayes

## 📌 Project Overview

This project performs **Sentiment Analysis** on IMDb movie reviews using **Natural Language Processing (NLP)** and **Machine Learning**.

The goal is to classify movie reviews as:

- 😊 Positive
- 😞 Negative

The review text is converted into numerical features using **TF-IDF Vectorization**, and a **Multinomial Naive Bayes** classifier is used to predict sentiment.

---

## 🎯 Objective

To build a sentiment classification model that can automatically determine whether a movie review expresses a **positive** or **negative** opinion.

---

## 📂 Dataset Information

| Parameter | Value |
|------------|---------|
| Dataset | IMDb Movie Reviews |
| Total Reviews | 16,602 |
| Positive Reviews | 8,187 |
| Negative Reviews | 8,415 |
| Input Feature | Review Text |
| Target Variable | Sentiment |

### Sample Data

| Review | Sentiment |
|----------|----------|
| This movie was fantastic and amazing | Positive |
| Worst movie I have ever watched | Negative |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Google Colab

---

## 📊 Project Workflow

```text
IMDb Dataset
      │
      ▼
Load Dataset
      │
      ▼
Data Analysis
      │
      ▼
Train-Test Split
(80% Train, 20% Test)
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Multinomial Naive Bayes
      │
      ▼
Prediction
      │
      ▼
Accuracy Evaluation
      │
      ▼
Confusion Matrix
      │
      ▼
Classification Report
      │
      ▼
Custom Review Testing
```

---

## 🔄 Train-Test Split

| Dataset | Records | Percentage |
|----------|---------:|-----------:|
| Training Data | 13,281 | 80% |
| Testing Data | 3,321 | 20% |
| Total Reviews | 16,602 | 100% |

---

## 🧠 TF-IDF Vectorization

TF-IDF stands for:

**Term Frequency – Inverse Document Frequency**

It converts text into numerical values and assigns higher importance to meaningful words.

### TF-IDF Output Shape

| Dataset | Shape |
|----------|---------|
| Training Data | (13281, 59122) |
| Testing Data | (3321, 59122) |

### Interpretation

| Item | Value |
|---------|---------|
| Training Reviews | 13,281 |
| Testing Reviews | 3,321 |
| Unique Words | 59,122 |

---

## 🤖 Machine Learning Model

### Algorithm Used

**Multinomial Naive Bayes**

### Why Multinomial Naive Bayes?

- Suitable for text classification
- Fast training
- Works efficiently with TF-IDF features
- Good performance on sentiment analysis

---

## 📈 Model Performance

### Accuracy

| Metric | Value |
|----------|---------|
| Accuracy | 85.31% |

### Interpretation

The model correctly classified approximately **85 out of every 100 movie reviews**.

---

## 📉 Confusion Matrix

| Actual \ Predicted | Negative | Positive |
|-------------------|---------:|---------:|
| Negative | 1512 | 138 |
| Positive | 350 | 1321 |

### Analysis

| Metric | Value |
|----------|---------:|
| Correct Negative Predictions | 1512 |
| Correct Positive Predictions | 1321 |
| Total Correct Predictions | 2833 |
| Total Wrong Predictions | 488 |
| Total Test Reviews | 3321 |

---

## 📋 Classification Report

| Sentiment | Precision | Recall | F1-Score | Support |
|------------|-----------:|--------:|---------:|---------:|
| Negative | 0.81 | 0.92 | 0.86 | 1650 |
| Positive | 0.91 | 0.79 | 0.84 | 1671 |

### Overall Performance

| Metric | Value |
|----------|---------:|
| Accuracy | 85% |
| Macro Avg F1-Score | 85% |
| Weighted Avg F1-Score | 85% |

---

## 🔍 Custom Review Prediction

### Example 1

```python
review = ["This movie was fantastic and amazing"]
```

Output:

```text
Positive
```

### Example 2

```python
review = ["Worst movie I have ever watched"]
```

Output:

```text
Negative
```

---

## 💡 Key Learnings

- Text data must be converted into numerical form before applying machine learning.
- TF-IDF assigns importance to meaningful words.
- Multinomial Naive Bayes performs effectively for text classification tasks.
- Confusion Matrix and Classification Report help evaluate model performance.

---

## 🚀 Results

| Parameter | Result |
|------------|---------|
| NLP Technique | TF-IDF Vectorizer |
| Algorithm | Multinomial Naive Bayes |
| Accuracy | 85.31% |
| Classification Type | Positive / Negative |
| Project Status | Successfully Completed |

---

## ✅ Conclusion

The IMDb Movie Review Sentiment Analysis project successfully classified movie reviews as **Positive** or **Negative** using **TF-IDF Vectorization** and the **Multinomial Naive Bayes** algorithm.

The model achieved an accuracy of **85.31%**, demonstrating that NLP techniques can effectively analyze textual opinions and predict sentiment from movie reviews.

---

## 👨‍💻 Prepared by

**Sugumar Ranganathan, M.B.A.,**

Email: contact.sugumarai@gmail.com

GitHub: https://github.com/sugumarranganathan
