# 📚 Sentiment Analysis on Amazon Kindle Reviews

## Overview

This project performs sentiment analysis on Amazon Kindle Store book reviews using classical Natural Language Processing (NLP) techniques and Machine Learning models.
The goal is to classify reviews as **positive (1)** or **negative (0)** based on their text content.

## Dataset

The dataset is a subset of Amazon Kindle Store reviews containing user feedback and ratings.

**Features used**

* `reviewText` — Review text
* `rating` — Converted into sentiment label

  * Rating < 3 → Negative (0)
  * Rating ≥ 3 → Positive (1)

## Workflow

1. Data Cleaning & Preprocessing

   * Lowercasing text
   * Removing special characters, URLs, HTML tags
   * Stopword removal
   * Lemmatization

2. Feature Extraction

   * Bag of Words (BoW)
   * TF-IDF

3. Model Training

   * Naive Bayes Classifier

4. Evaluation

   * Accuracy Score
   * Confusion Matrix
   * Classification Report

## Libraries Used

* pandas
* nltk
* scikit-learn
* BeautifulSoup

## Results

The model demonstrates baseline sentiment classification performance using traditional NLP pipelines and vectorization methods.

## Future Improvements

* Word2Vec / Embeddings
* Deep Learning models (LSTM / Transformers)
* Hyperparameter tuning
* Handling class imbalance

---

⭐ This project is part of my learning journey in NLP and Machine Learning.
