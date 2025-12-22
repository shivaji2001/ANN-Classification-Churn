<h3>Deployed Link:- https://ann-classification-churn-ngdyhwz62ey7bqneacoqer.streamlit.app/</h3>



<div align="center">

# 🏦 Customer Churn Prediction

### A Deep Learning Web Application powered by TensorFlow & Streamlit

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://your-app-url-here.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)




</div>

---

## 🚀 Overview

**Customer Churn Prediction** is an end-to-end Deep Learning application designed to help businesses retain customers. By analyzing demographic and financial data, the Artificial Neural Network (ANN) predicts the likelihood of a customer leaving the bank.

This project demonstrates the full machine learning pipeline: from data preprocessing and feature engineering to model training and deployment via a web interface.

## ✨ Key Features

- **🧠 Deep Learning Engine:** Utilizes a Multi-Layer Perceptron (ANN) built with **TensorFlow/Keras**.
- **⚡ Real-Time Inference:** Instant churn probability calculations based on user inputs.
- **🎨 Interactive UI:** A clean, user-friendly interface built with **Streamlit**.
- **🔄 Automated Preprocessing:** Integrated pipelines for Label Encoding, One-Hot Encoding, and Feature Scaling (StandardScaler).

## 🛠️ Technologies Used

| Category | Technologies |
|:---:|:---|
| **Frontend** | Streamlit |
| **Deep Learning** | TensorFlow, Keras |
| **Data Processing** | Pandas, NumPy, Scikit-Learn |
| **Model Serialization** | Pickle |
| **Version Control** | Git, GitHub |

---

## 📂 Project Structure

```bash
ANN-Classification-Churn/
├── app.py                   # Main Streamlit application entry point
├── experiments.ipynb        # Jupyter Notebook for EDA and Model Training
├── model.h5                 # Trained Keras ANN model
├── label_encoder_gender.pkl # Serialized Label Encoder (Gender)
├── onehot_encoder_geo.pkl   # Serialized OneHot Encoder (Geography)
├── scaler.pkl               # Serialized Standard Scaler
├── requirements.txt         # Project dependencies
└── README.md                # Project documentation

⚙️ Installation & Setup
Follow these steps to run the app locally on your machine.

1. Clone the Repository
git clone [https://github.com/shivaji2001/ANN-Classification-Churn.git](https://github.com/shivaji2001/ANN-Classification-Churn.git)
cd ANN-Classification-Churn

2. Create a Virtual Environment (Optional but Recommended)
python -m venv venv
# Windows
.\venv\Scripts\activate
# Mac/Linux
source venv/bin/activate

3. Install Dependencies
pip install -r requirements.txt

4. Run the Application
streamlit run app.py
