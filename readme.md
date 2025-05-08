# 🌾 Crop Price Prediction Web App

A machine learning-powered web application to predict future crop prices based on crop type, state, month, and years. Built using **Flask**, **HTML/CSS**, and trained models in Python.

## 🚀 Features

- Crop price prediction using machine learning models
- Interactive web interface for user input
- Flask backend for model serving
- Clean UI with index and result pages
- Support for ARIMA, Prophet, and LSTM evaluation (included in script)

---

## 🧠 Models Used

- **Classification Model** (`crop_price_model.pkl`)
- **Scaler** (`scaler.pkl`)
- Time-series models evaluated: ARIMA, Prophet, LSTM (see `mae_&_rmse(crop).py`)

---

## 📁 Project Structure

├── app.py # Flask backend
├── crop_price_model.pkl # Trained classification model
├── scaler.pkl # Scaler used in preprocessing
├── crop_price_prediction_data.csv # Dataset used for encoding
├── index.html # Frontend input form
├── result.html # Result display page
├── mae_&_rmse(crop).py # Script to evaluate ARIMA, Prophet, and LSTM
└── README.md # Project documentation

/

🔍 Screenshots
🌱 Input Page (index.html)
User selects crop, state, month, current year, and future year.


📊 Result Page (result.html)
Displays predicted crop price based on input.

📬 Contact
For feedback or collaboration, reach out via GitHub issues or email.

