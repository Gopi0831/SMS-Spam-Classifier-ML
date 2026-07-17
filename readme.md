# 📧 SMS Spam Message Classifier using Machine Learning

## 📌 Project Overview

This project is a Machine Learning-based SMS Spam Message Classifier that automatically classifies SMS messages as **Spam** or **Ham (Normal)** using Natural Language Processing (NLP).

The model converts text messages into numerical features using **CountVectorizer** and classifies them using a **Logistic Regression** algorithm.

---

## 🎯 Objective

To build an intelligent spam detection system capable of identifying unwanted SMS messages with high accuracy.

---

## 📂 Dataset

**Dataset Name:** SMS Spam Collection Dataset

Features:

- **label** → ham / spam
- **message** → SMS text

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- Matplotlib
- CountVectorizer
- Logistic Regression

---

## 🔄 Project Workflow

1. Import Libraries
2. Load Dataset
3. Explore Dataset
4. Data Preprocessing
5. Feature Extraction using CountVectorizer
6. Train-Test Split
7. Train Logistic Regression Model
8. Model Evaluation
9. Custom Message Prediction
10. Prediction Confidence

---

## 📊 Model Performance

| Metric | Value |
|---------|--------|
| Algorithm | Logistic Regression |
| Feature Extraction | CountVectorizer |
| Accuracy | **98.83%** |

---

## 📈 Evaluation Metrics

The model was evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score

---

## 📩 Example Prediction

**Input**

Congratulations! You have won a free iPhone. Click here to claim your prize.

**Prediction**

Spam ✅

---

## 🚀 Future Improvements

- Deploy using Streamlit
- Improve text preprocessing
- Compare additional ML algorithms
- Use Deep Learning (LSTM/BERT)
- Create a web application

---

## 📁 Project Structure

```
SMS-Spam-Classifier/
│
├── Spam_Classifier_Final.ipynb
├── README.md
└── dataset
```

---

## 👨‍💻 Author

**Gopi Krishnan**

B.Tech – Artificial Intelligence and Data Science

GitHub:  https://github.com/Gopi0831
LinkedIn:  https://www.linkedin.com/in/gopi-krishnan-a-1520-/
