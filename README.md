# 📧 Spam Email Detection using Machine Learning Models

## 🚀 Project Description

This project focuses on building an intelligent system to classify emails as **Spam** or **Ham (Not Spam)** using multiple machine learning algorithms. The primary objective is to perform a **comparative analysis of different models** on the same dataset and evaluate their performance using various metrics.

The project demonstrates how traditional machine learning techniques can effectively solve real-world Natural Language Processing (NLP) problems like spam detection.

---

## 📂 Dataset Description

The dataset used in this project consists of labeled email messages categorized into two classes:

* **Spam (1):** Unwanted or promotional emails
* **Ham (0):** Legitimate emails

### Key Characteristics:

* Type: Text dataset (NLP)
* Task: Binary classification
* Format: CSV file
* Features:

  * `text` → Email content
  * `label` → Target variable (spam/ham)

### Data Challenges:

* Imbalanced dataset (more ham than spam)
* Requires preprocessing and feature extraction

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

* Converted text to lowercase
* Removed URLs and special characters
* Removed unnecessary symbols
* Cleaned and normalized text

---

## 🧠 Feature Extraction

Text data was converted into numerical format using:

### 🔹 TF-IDF (Term Frequency – Inverse Document Frequency)

* Captures importance of words in a document
* Helps identify spam-related keywords like *“free”, “win”, “offer”*

---

## 🤖 Machine Learning Models Used

The project implements and compares the following models:

1. **Naive Bayes**
2. **Logistic Regression**
3. **Support Vector Machine (SVM)**
4. **Random Forest**
5. **XGBoost**

---

## 📊 Evaluation Metrics

To evaluate model performance, the following metrics were used:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 📈 Results & Insights

* **XGBoost and SVM achieved the highest accuracy**, demonstrating strong performance on high-dimensional text data.
* **Naive Bayes performed well as a baseline model** due to its efficiency in text classification tasks.
* TF-IDF significantly improved model performance by highlighting important words.

---

## 📊 Visualization

* Bar chart comparing accuracy of all models
* Confusion matrix for performance analysis

---

## 🛠️ Tech Stack

* Python
* Scikit-learn
* XGBoost
* Pandas, NumPy
* Matplotlib

---

## ▶️ How to Run

1. Install dependencies:

```bash
pip install kagglehub scikit-learn xgboost pandas numpy matplotlib
```

2. Run the script:

```bash
python main.py
```

---

## 🎯 Key Learnings

* Importance of feature extraction in NLP
* Comparison between different ML models
* Handling imbalanced datasets
* Model evaluation using multiple metrics

---

## 🔮 Future Scope

* Implement Deep Learning models (LSTM, BERT)
* Build a web interface using Streamlit
* Deploy the model as an API


