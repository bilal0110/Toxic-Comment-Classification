# 🛑 Toxic Comment Classification

## 🧩 Problem
Online platforms receive thousands of comments — some of them harmful.  
This project detects **toxic behavior in text** using machine learning.

---

## 🏷️ Labels
Each comment can belong to one or more categories:

- toxic  
- severe_toxic  
- obscene  
- threat  
- insult  
- identity_hate  

👉 This is a **multi-label classification problem**

---

## 🧠 Approach
- Convert text into numerical features  
- Train models to predict multiple labels  
- Use **One-vs-Rest strategy** for handling multi-label outputs  

---

## 🤖 Models Used
- Logistic Regression  
- Multinomial Naive Bayes  
- Wrapped with **OneVsRestClassifier**

---

## 📊 Evaluation
- Accuracy Score  
- ROC-AUC Score  
- Classification Report  
- ROC Curve  

---

## 🛠️ Tools
- Python  
- Scikit-learn  
- NLP preprocessing (tokenization, cleaning)  

---

## ▶️ Run

```bash
git clone https://github.com/your-username/toxic-comment-classification.git
cd toxic-comment-classification
pip install -r requirements.txt
python app.py
