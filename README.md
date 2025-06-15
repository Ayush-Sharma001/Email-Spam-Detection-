# 📧 Email Spam Detection using TF-IDF and Naive Bayes

This project is a machine learning-based spam classifier that detects whether an email (or SMS message) is **SPAM** or **HAM (Not Spam)**. It uses **TF-IDF vectorization** to convert text into feature vectors and applies a **Multinomial Naive Bayes** classifier to make predictions.

---

## 📁 Dataset

- Source: `spam.csv`
- Contains two columns:
  - `v1`: Label (ham/spam)
  - `v2`: Message content

---

## 🧠 Machine Learning Stack

- **Text Processing**
  - Lowercasing
  - Punctuation removal
  - Stopword removal (using NLTK)
- **Feature Extraction**
  - TF-IDF Vectorization
- **Model**
  - Multinomial Naive Bayes
- **Evaluation**
  - Accuracy
  - Confusion Matrix
  - Classification Report

---

## 🚀 How to Use

1. Clone the repository
2. Install requirements: pip install -r requirements.txt
3. Example :- Enter a message to check if it's SPAM or HAM:
              > Congratulations! You've won a 1000$ 
                Prediction: SPAM


