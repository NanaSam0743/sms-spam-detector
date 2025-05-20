# 📱 SMS Spam Detection using Machine Learning

This project is a part of my Machine Learning Internship at @Indolike.  
It focuses on building a machine learning model that can classify SMS messages as **Spam** or **Ham (not spam)** using natural language processing (NLP) techniques.

## 📌 Description
The goal of this project is to develop a simple and accurate spam classifier for SMS messages.  
Using the **SMS Spam Collection Dataset**, the text data is cleaned, vectorized using **TF-IDF**, and modeled with a **Multinomial Naive Bayes classifier**, which is a strong baseline for text classification tasks.

## 🧠 Technologies & Tools
- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Naive Bayes Classifier
- Matplotlib & Seaborn (for visualization)

## 📊 Model Performance
The model achieves over **95% accuracy** on the test set and shows strong performance across precision and recall metrics.

## 📁 Dataset
- [Kaggle - SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

## 🔍 Steps Involved
1. Data loading & preprocessing
2. Text cleaning (removing punctuation, lowercasing, etc.)
3. Label encoding (spam = 1, ham = 0)
4. Train-test split
5. TF-IDF vectorization
6. Naive Bayes training
7. Evaluation (accuracy, confusion matrix, classification report)

## 🚀 How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
