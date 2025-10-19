# 💳 Credit Card Fraud Detection System

An interactive web application built using **Python**, **Streamlit**, and **LightGBM** to detect fraudulent credit card transactions in real time.  
The system takes in transaction details such as amount, location, and merchant information, and predicts whether a transaction is **fraudulent or legitimate**.

---

## 🚀 Project Overview

This project demonstrates an **end-to-end fraud detection pipeline** — from data preprocessing and model training to deployment.  
The model uses **LightGBM**, a high-performance gradient boosting framework, and is integrated into a **Streamlit web app** for easy user interaction.

---

## 🧠 Key Features

- Real-time **fraud detection** based on user input  
- Calculates **distance** between customer and merchant using geolocation  
- Encodes categorical features dynamically (handles unseen labels)  
- Uses **LightGBM** for fast, high-accuracy predictions  
- Clean and simple **Streamlit interface** for users  

---

## 📚 Topics Covered

- Data preprocessing and feature encoding  
- Feature engineering (geospatial distance, hashing, time features)  
- Handling unseen categories in real-time prediction  
- Model deployment using **Streamlit**  
- Interactive UI design for fraud detection apps  

---

## 🧰 Tech Stack

- **Language:** Python  
- **Framework:** Streamlit  
- **Model:** LightGBM  
- **Libraries:** Pandas, NumPy, Joblib, Geopy, Scikit-learn  
- **Deployment:** Local or cloud-hosted Streamlit app  

---

## 🗂️ Project Structure
```
📂 Credit_Card_Fraud_Detection/
│   ├── app.py                      # Streamlit app script
│   ├── fraud_detection_model.jb    # Trained LightGBM model
│   ├── label_encoders.jb           # Encoders for categorical variables
|   ├── requirements.txt            # Dependencies
|   ├── README.md                   # Project documentation
```
