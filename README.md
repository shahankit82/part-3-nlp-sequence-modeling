# Part 3: NLP and Sequence Modeling

## 📌 Overview

This project explores text classification using both traditional NLP methods and sequence-based deep learning models.

---

## 🧠 Objectives

* Convert text into numerical representations
* Compare TF-IDF with sequence modeling
* Build baseline and LSTM models

---

## 📊 Dataset

* Text-based customer support data
* Multiple categories (labels)
* Task: classify text into categories

---

## ⚙️ Preprocessing

* Lowercasing
* Removing special characters
* Stopword removal
* Tokenization

---

## 🔢 Vectorization Methods

* TF-IDF (baseline)
* Explanation : Text must be converted into vectors because machine learning models work with numerical data. Techniques like TF-IDF represent words as numbers based on their importance in a document.
* Tokenizer + sequences (deep learning)

---

## 🤖 Models

### Baseline

* Logistic Regression with TF-IDF

### Sequence Model

* Embedding layer
* LSTM layer
* Dense output

---

## 📈 Results

* Evaluation metrics saved in `/results`
* Sample predictions included

---

## 🧠 Key Learnings

* Text must be converted into vectors
* TF-IDF captures importance
* LSTM captures sequence context
