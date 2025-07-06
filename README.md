# 🐦 Twitter Sentiment Analysis

This project performs **sentiment analysis on tweets** using natural language processing (NLP) and a **Logistic Regression** model. The system predicts whether a tweet expresses a **positive** or **negative** sentiment based on the text content.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas & NumPy** 
- **NLTK** 
- **Scikit-learn** 
- **Logistic Regression** 

---

## 🧠 Features

- Text preprocessing (cleaning, lowercasing, stemming)
- TF-IDF vectorization of tweet content
- Sentiment classification using Logistic Regression
- Accuracy reporting for both training and test sets
- Custom tweet prediction support

---


## ⚙️ How It Works

1. **Preprocessing**
   - Remove non-alphabet characters
   - Lowercase conversion
   - Stopword removal
   - Word stemming using Porter Stemmer

2. **Feature Extraction**
   - TF-IDF Vectorization on cleaned tweets

3. **Modeling**
   - Train/Test split
   - Logistic Regression model with `max_iter=1000`
   - Performance evaluated using `accuracy_score`

4. **Prediction**
   - Predict sentiment of new/unseen tweet samples
