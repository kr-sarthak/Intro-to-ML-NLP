# 📘 Intro to Machine Learning and NLP

### 🧠 Course Project – Introduction to Machine Learning and Natural Language Processing  
**Student**: Kumar Sarthak
**Program**: *Mtech BME*  

---

## 🧠 Overview

This repository contains hands-on projects for learning core concepts in **Machine Learning (ML)** and **Natural Language Processing (NLP)**. It includes:

- 🔤 Text vectorization using **CountVectorizer** and **TF-IDF**
- 💬 Sentiment classification on synthetic:
  - 🎬 Movie reviews
  - 📦 Product reviews
- 🧠 Machine learning models:
  - **Multinomial Naive Bayes**
  - **Logistic Regression**
- 📊 Evaluation using accuracy, precision, recall, F1-score

---

## 📁 Files

| File | Description |
|------|-------------|
| `problem4_movie_sentiment.py` | Movie review sentiment classification using CountVectorizer + Naive Bayes |
| `problem5_product_sentiment.py` | Product review sentiment classification using TF-IDF + Logistic Regression |
| `dataset_generator.py` | Generates synthetic movie/product reviews |
| `README.md` | Project documentation |
| `requirements.txt` | Python packages required to run the code |

---

## 📽️ Problem 4: Movie Review Classification

- **Dataset**: 100 synthetic reviews (50 positive, 50 negative)
- **Vectorizer**: CountVectorizer (max 500 features, English stop words removed)
- **Model**: Multinomial Naive Bayes
- **Output**: Accuracy on test set, review prediction function

---

## 📦 Problem 5: Product Review Classification

- **Dataset**: 100 synthetic product reviews (50 good, 50 bad)
- **Vectorizer**: TF-IDF (max 300 features)
- **Model**: Logistic Regression
- **Evaluation**: Accuracy, precision, recall, F1-score
- **Functionality**: Real-time prediction from user input

---

## 🔍 Sample Output

