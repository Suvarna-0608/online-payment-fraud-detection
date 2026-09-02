# Online Payment Fraud Detection System

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20App-000000)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This project is designed to enhance the security of online financial transactions by identifying and flagging fraudulent payment activities. In the rapidly evolving landscape of digital commerce, ensuring the integrity of payments is crucial. This system provides a robust mechanism to help prevent financial losses due to illicit transactions.

---

## 🔑 Key Features & Pipeline

* **Data Preprocessing & EDA**: Analysis of transactional patterns, balance changes, and distribution using interactive Jupyter Notebooks (`EDA.ipynb`).
* **Fraud Detection Model**: Machine Learning model trained on historical payment data to classify transactions as legitimate or fraudulent (`model.ipynb`).
* **Flask Web Interface**: Interactive user interface allowing users to submit transaction parameters and receive real-time fraud predictions (`app.py`).
* **Model Serialization**: Serialized ML pipeline (`payment.pkl`) integrated directly into the web server for fast inference.

---

## 🛠️ Tech Stack

* **Language**: Python 3.8+
* **Machine Learning & Analysis**: Scikit-Learn, Pandas, NumPy, Jupyter Notebook
* **Web Framework**: Flask
* **Frontend**: HTML5, CSS3
* **Model Export**: Pickle (`payment.pkl`)

---

## 📁 Project Structure

```text
online-payment-fraud-detection/
│
├── flask/                         # Web Application Workspace
│   ├── templates/                # Front-end UI (home, predict, submit)
│   ├── app.py                    # Flask application entry point
│   ├── payment.pkl              # Serialized prediction model
│   └── requirements.txt          # Web app Python dependencies
│
├── python notebook/training/      # ML Development & Exploration
│   ├── EDA.ipynb                 # Data exploration notebook
│   ├── model.ipynb               # Model training pipeline
│   └── payment.pkl              # Trained model artifact
│
└── README.md                      # Documentation
