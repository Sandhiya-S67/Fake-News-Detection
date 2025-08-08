
---

# Fake News Detection

## Overview

This project detects whether a given news article is **real** or **fake** using Natural Language Processing (NLP) and machine learning techniques.
It processes a dataset of news articles, extracts meaningful features, trains a classification model, and evaluates its performance.

---

## Dataset

The project uses the **Fake and Real News Dataset** containing:

* **True.csv** – Real news articles.
* **Fake.csv** – Fake news articles.

**Note:**
## Dataset
Due to GitHub's file size limit, the full dataset is available here:
[Download Dataset from Google Drive](https://drive.google.com/drive/folders/1ByadNwMrPyds53cA6SDCHLelTAvIdoF_)


---

## Features

* **Data Preprocessing**

  * Remove punctuation, special characters, and stopwords
  * Tokenization
  * Lowercasing
* **Feature Extraction**

  * TF-IDF Vectorization
* **Model Training**

  * Logistic Regression (can be replaced with other models)
* **Evaluation**

  * Accuracy, Precision, Recall, and F1-score
  * Confusion Matrix visualization

---

## Results

The Logistic Regression model achieves high accuracy in detecting fake news.
The notebook includes detailed preprocessing, feature extraction, training, and evaluation steps for reproducibility.

---
