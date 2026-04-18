# 🍽️ Restaurant Review Sentiment Analysis

## 🚀 Overview
This project performs sentiment analysis on restaurant reviews using Natural Language Processing (NLP) techniques.

The goal is to classify reviews as:
- Positive 😊  
- Negative 😠  

---

## 📊 Dataset
- Restaurant Reviews dataset :contentReference[oaicite:0]{index=0}  
- Features:
  - Review (text)  
- Target:
  - 0 → Negative  
  - 1 → Positive  

---

## ⚙️ Approach

### 🔹 Data Preprocessing
- Removed punctuation and special characters  
- Converted text to lowercase  
- Removed stopwords  
- Applied stemming  

---

### 🔹 Feature Extraction
- Used **Bag of Words (BoW)**  
- Converted text into numerical vectors  

---

## 🧠 Models Used

Multiple classification models were tested:

| Model | Accuracy |
|------|---------|
| Linear SVM | 79% |
| Kernel SVM | 78% |
| Logistic Regression | 77.5% |
| Random Forest / Decision Tree | 75% |
| Naive Bayes | 73% |
| KNN | 69% |

---

## 🏆 Best Model
👉 **Linear SVM performed the best (79% accuracy)**  

---

## 🧠 Key Insights
- Text preprocessing significantly impacts performance  
- SVM performs well for text classification  
- Bag of Words is simple yet effective for basic NLP tasks  

---

## ⚠️ Challenges Faced
- Cleaning noisy text data  
- Choosing the right model  
- Feature representation limitations  

---

## 🎯 Conclusion
Bag of Words combined with machine learning models provides a solid baseline for sentiment analysis tasks.

---

## 🔮 Future Improvements
- Use TF-IDF instead of BoW  
- Try deep learning models (LSTM)  
- Use word embeddings (Word2Vec, GloVe)  
