# 💳 Credit Card Fraud Detection

## 📌 Project Overview

An end-to-end Machine Learning pipeline that detects fraudulent credit card transactions, deployed as a high-performance REST API.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Imbalanced-learn (SMOTE)
* FastAPI (Production-grade Web Framework)
* Uvicorn (ASGI Web Server)
* Jupyter Notebook

## 📊 Dataset

Credit Card Fraud Detection Dataset (containing PCA-transformed features V1-V28, Time, Amount, and Class).

## 🚀 Cloud Deployment

The FastAPI backend is production-deployed on **Render**. 
* **Live API Endpoint:** `https://your-render-app-name.onrender.com` *(Apne Render app ka live link yahan dalein)*
* **Interactive API Docs (Swagger UI):** `https://your-render-app-name.onrender.com/docs`

## 💻 How to Run Locally

1. Clone the repository `git clone https://github.com/diwarak983/credit-card-fraud-detection.git`
2. Install dependencies `pip install fastapi uvicorn pandas numpy scikit-learn imbalanced-learn`
3. Run the FastAPI server `uvicorn app:app --reload`
4. Access local API documentation at `http://127.0.0.1:8000/docs`

## 📁 Project Structure

credit-card-fraud-detection/ ── fraud_detection.ipynb ── app.py ── fraud_model.pkl ── scaler.pkl ── requirements.txt ── README.md

## 🎯 Results

* **Model Architecture:** Highly optimized classification model with robust scaling.
* **Imbalance Handling:** SMOTE (Synthetic Minority Over-sampling Technique).
* **API Response Time:** Fast inference optimized via FastAPI's asynchronous capabilities.
