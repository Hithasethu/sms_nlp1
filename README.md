# sms_nlp1
# 📱 SMS Spam Detection Using Machine Learning

This project applies machine learning and NLP techniques to detect spam messages from SMS text. It uses a classic dataset split into training and testing sets and explores several supervised models to classify messages as "spam" or "ham" (not spam).

---

## 🎯 Objectives

- Preprocess SMS text data for analysis
- Train and evaluate spam classifiers using machine learning
- Compare model performance across various metrics
- Provide a scalable baseline for spam detection systems

---

## 📁 Files in This Project

| File                 | Description                                  |
|----------------------|----------------------------------------------|
| `sms.ipynb`          | Jupyter Notebook with full analysis pipeline |
| `SMS_train(1).csv`   | Training dataset (labeled)                   |
| `SMS_test(2).csv`    | Testing dataset (labeled)                    |
| `README.md`          | Project overview and instructions            |

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK or spaCy (if used)
- CountVectorizer / TfidfVectorizer
- Classifiers: Naive Bayes, Logistic Regression, etc.
- Jupyter Notebook

---

## 📊 Workflow Overview

1. **Data Loading**
   - Load `SMS_train(1).csv` and `SMS_test(2).csv`
   -Merge both training and testing

2. **Text Preprocessing**
   - Lowercasing, punctuation removal
   - Tokenization and stopword removal
   - Vectorization (TF-IDF or Bag-of-Words)

3. **Model Building**
   - Train classifiers (e.g., Naive Bayes, Logistic Regression)
   - Evaluate using metrics like Accuracy, Precision, Recall, F1-score

4. **Testing**
   - Generate predictions and performance reports

---

## ✅ Example Results



- **Randum forest Accuracy**: 96%  
- **Naive bayes**: 98.1%   
- **Confusion Matrix**: Clearly shows minimal false positives

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Hithasethu/sms-nlp1.git
   cd sms-nlp1
