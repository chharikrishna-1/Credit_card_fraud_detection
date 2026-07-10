# 💳 Credit Card Fraud Detection System

An AI-powered Credit Card Fraud Detection web application built using **Python, Flask, XGBoost, HTML, CSS, and Machine Learning**. The system predicts whether a transaction is **Legitimate** or **Fraudulent** based on transaction details and displays the fraud probability, risk level, and recommendation in real time.

---

## 🚀 Features

- 🔍 Real-time fraud detection
- 🤖 Machine Learning model using XGBoost
- 📊 Fraud probability prediction
- ⚠️ Risk level classification
- 💡 Recommendation based on prediction
- 📱 Responsive and user-friendly interface
- 🌍 Supports foreign transaction detection
- 📍 Detects location mismatch
- 📈 Displays model accuracy and prediction details

---

## 🛠️ Technologies Used

- Python
- Flask
- XGBoost
- Pandas
- NumPy
- Scikit-learn
- HTML5
- CSS3

---

## 📂 Project Structure

```
Credit_card_fraud_detection/
│
├── app.py
├── fraud_model.pkl
├── scaler.pkl
├── label_encoder.pkl
├── credit_card_fraud.csv
├── credit program.py
│
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/chharikrishna-1/Credit_card_fraud_detection.git
```

### Move into the project

```bash
cd Credit_card_fraud_detection
```

### Install dependencies

```bash
pip install flask pandas numpy scikit-learn xgboost joblib
```

---

## ▶️ Run the Project

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## 📋 Input Features

- Transaction Amount
- Transaction Hour
- Device Trust Score
- Transactions in Last 24 Hours
- Cardholder Age
- Merchant Category
- Foreign Transaction
- Location Mismatch

---

## 📊 Output

The application displays:

- Prediction (Legitimate / Fraud)
- Fraud Probability
- Risk Level
- Recommendation
- Transaction Details
- Detection Time
- Model Information

---

## 🧠 Machine Learning Model

- Algorithm: XGBoost Classifier
- Data Preprocessing:
  - Label Encoding
  - Feature Scaling
  - SMOTE Oversampling
- Model saved using Pickle (.pkl)

---

## 📸 Screenshots




### Home Page

<img width="1920" height="1080" alt="Screenshot 2026-07-10 182512" src="https://github.com/user-attachments/assets/490a5265-6406-4e1b-bfec-69ae66d168c0" />

### Prediction Result

<img width="1920" height="1080" alt="Screenshot 2026-07-10 191709" src="https://github.com/user-attachments/assets/8e7e88b6-51aa-45db-a997-55cd50c94dc7" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0b7167d9-ca18-4a4d-b724-8b925156d6fd" />

## 📈 Future Improvements

- User Authentication
- Database Integration
- Email/SMS Fraud Alerts
- Transaction History
- Live Payment Gateway Integration
- Dashboard with Analytics

---

## 👨‍💻 Author

**Hari Krishna**

GitHub: https://github.com/chharikrishna-1

---

## ⭐ If you like this project

Please consider giving it a ⭐ on GitHub!
