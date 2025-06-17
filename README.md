# Intro-to-ML-NLP
README – Intro to Machine Learning and NLP Project

Course: Introduction to Machine Learning and Natural Language Processing
Student: Kumar Sarthak
IITB BME

Overview
This project introduces core ML and NLP techniques using Python. It includes:

Text vectorization: CountVectorizer & TF-IDF

Sentiment classification (positive vs. negative/good vs. bad)

Use of Naive Bayes and Logistic Regression models

Evaluation using accuracy, precision, recall, and F1-score

Files

problem4_movie_sentiment.py: Movie review classifier using CountVectorizer and Naive Bayes

problem5_product_sentiment.py: Product review classifier using TF-IDF and Logistic Regression

dataset_generator.py: Helper code to generate synthetic reviews

README.md: Project overview

requirements.txt (optional): Required Python libraries

Problem 4 – Movie Review Classification

Dataset: 100 synthetic reviews (50 positive, 50 negative)

Preprocessing: CountVectorizer with max 500 features, stop word removal

Model: Multinomial Naive Bayes

Evaluation: 80/20 train/test split with accuracy

Includes: Prediction function for custom input

Problem 5 – Product Review Classification

Dataset: 100 synthetic product reviews (50 good, 50 bad)

Preprocessing: TF-IDF with max 300 features

Model: Logistic Regression

Evaluation: Accuracy, precision, recall, F1-score

Includes: Vectorization + prediction function
