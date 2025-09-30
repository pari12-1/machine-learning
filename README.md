# 📧 Spam Email Detection using Scikit-learn

This project demonstrates how to **build a predictive model** using **Scikit-learn** to classify SMS/email messages as **Spam** or **Ham (not spam)**.  
It uses a **Naive Bayes classifier** with a Bag of Words text representation.

---

## 🚀 Project Overview
- **Goal**: Predict whether a given message is spam or not.
- **Dataset**: [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)
- **Algorithm**: Multinomial Naive Bayes
- **Vectorization**: CountVectorizer (Bag of Words)

---

## 📂 Steps Implemented
1. **Import libraries** – Pandas, NumPy, Scikit-learn  
2. **Load dataset** – Pre-labeled SMS dataset  
3. **Preprocess data** – Convert labels (`spam` → 1, `ham` → 0)  
4. **Split dataset** – Training (80%) and Testing (20%)  
5. **Feature extraction** – Transform text into numerical vectors  
6. **Model training** – Train Naive Bayes classifier  
7. **Model evaluation** – Accuracy, Precision, Recall, F1-score, Confusion Matrix  
8. **Predictions** – Test on sample messages  

---


---

## 🛠️ Requirements
- Python 3.x  
- pandas  
- numpy  
- scikit-learn  

Install dependencies with:
```bash
pip install pandas numpy scikit-learn
```
