# Emotion Classification from Tweets using SVM

This project implements a text classification pipeline using **Support Vector Machines (SVM)** to classify the emotional content of tweets. The goal is to predict one of six basic emotions expressed in English-language tweets using different SVM kernel functions and determine which provides the best classification performance.

## 📌 Project Overview

Social media platforms like Twitter provide rich sources of emotional expression. Automatically classifying emotions from text-based content has many applications, such as:

- Sentiment analysis
- Mental health monitoring
- Customer feedback analysis

This project uses a labeled dataset (`emotions.csv`) of tweets to build an emotion classifier based on SVM.

## 🧠 Objective

- Clean and preprocess tweet text data
- Convert text to numerical features using TF-IDF
- Train and evaluate SVM models using various kernels (`linear`, `rbf`, `poly`, `sigmoid`)
- Identify the kernel with the best classification performance

## 🛠️ Technologies Used

- Python 3
- Pandas
- Scikit-learn
- Regular Expressions
- TF-IDF Vectorization


