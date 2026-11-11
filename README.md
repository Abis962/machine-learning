Sentiment Analysis using Naive Bayes is a Natural Language Processing (NLP) project built with Python and Scikit-Learn[cite: 3]. It classifies movie reviews into positive and negative sentiments by analyzing text patterns using Bag of Words and TF-IDF feature extraction techniques[cite: 3].

## 🚀 Live Demo

[Click here to view the live app!](https://your-sentiment-demo-link.com)

---

## 🛠️ Features

* **Corpus Classification:** Analyzes 2,000 movie reviews (1,000 positive and 1,000 negative) sourced from NLTK's `movie_reviews` dataset[cite: 3].
* **Text Preprocessing & Detokenization:** Reconstructs tokenized reviews into clean text strings, correcting punctuation spacing and contractions[cite: 3].
* **Dual Vectorization Approaches:** Evaluates both CountVectorizer (Bag of Words) and TfidfVectorizer with stop-word removal and term frequency pruning[cite: 3].
* **Multinomial Naive Bayes Modeling:** Achieves up to 82.0% accuracy with TF-IDF, comparing confusion matrices and classification metrics against baseline counts[cite: 3].

---

## 💻 Tech Stack

* **Language:** Python[cite: 3]
* **NLP Toolkit:** NLTK (`movie_reviews`, MosesDetokenizer)[cite: 3]
* **Machine Learning:** Scikit-Learn (`MultinomialNB`, `CountVectorizer`, `TfidfVectorizer`)[cite: 3]
* **Data Manipulation:** Pandas, NumPy[cite: 3]

---

## 📊 Results Summary

| Vectorizer | Test Accuracy | Correctly Classified | Incorrectly Classified |
| :--- | :--- | :--- | :--- |
| **CountVectorizer (BoW)** | 79.8%[cite: 3] | 399 / 500[cite: 3] | 101 / 500[cite: 3] |
| **TF-IDF Vectorizer** | **82.0%**[cite: 3] | **410 / 500**[cite: 3] | **90 / 500**[cite: 3] |

---


