# 📰 Fake News Detection using Machine Learning  

## 📌 Project Overview  
This project is a **machine learning-based Fake News Detection System**.  
It takes in a news article and classifies it as **REAL or FAKE** using **Natural Language Processing (NLP)** and **Logistic Regression**.  

The main goal is to preprocess raw text data, convert it into numerical form using **TF-IDF Vectorization**, and then train a classifier to detect fake news effectively.  

---

## 📂 About The Dataset
- **id** : unique id of the news article  
- **title** : the title of a news article  
- **author** : author of the news article  
- **text** : the text of the article (may be incomplete)  
- **label** : a label that marks whether the news article is real or fake  
  - `1` : fake news  
  - `0` : real news  

---

## 🚀 Tech Stack / Libraries Used  
- **Python 3**  
- **NumPy** – numerical computations  
- **Pandas** – data manipulation & preprocessing  
- **NLTK** – text preprocessing (stopwords, stemming)  
- **scikit-learn** – ML model building & evaluation  
  - TfidfVectorizer  
  - Logistic Regression  
  - train_test_split  
  - accuracy_score, confusion_matrix  
- **Matplotlib / Seaborn** – visualization (confusion matrix heatmap)  

---

## 🔧 Project Workflow  
1. **Data Collection**  
   - Dataset: `train.csv` (contains labeled news articles).  

2. **Data Preprocessing**  
   - Remove special characters, numbers, and punctuation using `re`.  
   - Convert text to lowercase.  
   - Tokenization (split into words).  
   - Remove stopwords (NLTK stopwords).  
   - Apply **Porter Stemming** (e.g., “running” → “run”).  

3. **Feature Extraction**  
   - Convert cleaned text into numerical features using **TF-IDF Vectorizer**.  

4. **Model Training**  
   - Use **Logistic Regression** as the classification model.  

5. **Evaluation**  
   - Calculate **accuracy** on training & test data.  
   - Generate **confusion matrix**.  
   - Plot a **heatmap** for better visualization.  

---

## 📊 Results  
- Training Accuracy: ~ (your score here, e.g., 98%)  
- Test Accuracy: ~ (your score here, e.g., 96%)  
- Heatmap visualization to analyze correct vs. incorrect predictions.  

---
