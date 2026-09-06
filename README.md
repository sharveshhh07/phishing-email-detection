# Phishing Email Detection Model

## 📌 Project Description
A machine learning project that classifies emails as
"Phishing" or "Safe" using text-based features.

## 🎯 Objectives
- Train a machine learning model using email data
- Extract useful text features
- Classify emails as Phishing or Safe
- Evaluate the model using accuracy and confusion matrix

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn
- TF-IDF
- Logistic Regression
- Joblib

## ✨ Features
- Email dataset
- Text preprocessing and TF-IDF feature extraction
- Machine learning classification
- Accuracy evaluation
- Confusion matrix
- Prediction of new emails

## 📂 Project Structure

phishing-email-detection/
│
├── data/
│   └── emails.csv
├── src/
│   ├── train_model.py
│   └── predict.py
├── README.md
├── requirements.txt
└── .gitignore

## 📦 Installation

Install the required libraries:

pip install -r requirements.txt

## ▶️ Train the Model

python src/train_model.py

## 🔍 Test an Email

python src/predict.py --text "Urgent verify your account by clicking this link"

## 📊 Evaluation
The model displays:
- Accuracy
- Classification report
- Confusion matrix

## 🎓 Learning Outcome
This project helped me understand:
- Machine learning classification
- Natural Language Processing
- TF-IDF feature extraction
- Logistic Regression
- Model evaluation

## ⚠️ Disclaimer
This is an educational prototype. Real-world phishing
detection requires larger datasets and additional security signals.
