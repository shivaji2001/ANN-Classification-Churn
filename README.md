🏦 Customer Churn Prediction App
🚀 Overview
This is an end-to-end Deep Learning web application designed to predict customer churn. Built using TensorFlow and Streamlit, the app utilizes a trained Artificial Neural Network (ANN) to analyze customer demographics and financial data, determining the likelihood of a customer leaving the bank.

Customer churn prediction is a vital business metric, allowing companies to proactively identify at-risk customers and improve retention strategies.

✨ Key Features
Deep Learning Model: Powered by a Multi-Layer Perceptron (ANN) built with TensorFlow/Keras for high-accuracy classification.

Real-time Predictions: Users can input customer details (Credit Score, Geography, Age, Balance, etc.) and get instant churn probability results.

Interactive UI: A clean and simple web interface built with Streamlit.

Data Preprocessing: Handles categorical data encoding (Label Encoding & One-Hot Encoding) and feature scaling automatically using Scikit-Learn pipelines.

🛠️ Tech Stack
Frontend: Streamlit

Machine Learning: TensorFlow (Keras), Scikit-Learn

Data Processing: Pandas, NumPy

Model Storage: Pickle (for saving the trained model, scalers, and encoders)

📊 How It Works
Input Data: The user enters customer data (e.g., Credit Score, Geography, Gender, Age, Tenure, Balance, Number of Products, etc.) via the sidebar or main form.

Preprocessing: The app loads pre-trained encoders and scalers to transform the input data into the format required by the neural network.

Inference: The processed data is passed to the loaded ANN model.

Output: The model returns a probability score (0 to 1). If the probability is greater than 0.5, the customer is classified as "Likely to Churn"; otherwise, they are "Likely to Stay."
