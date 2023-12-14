# Fraud Detection Project

Overview

This project is aimed at building a fraud detection system using machine learning techniques. The model is trained on a dataset containing features related to financial transactions and is designed to identify potentially fraudulent activities.

Contents

data: (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
model: rf_model_f.pkl
src: Fraud_Detection_final.ipynb
final_app/: Streamlit web application for model deployment.
requirements.txt: List of Python dependencies for the project.
README.md: Project documentation.

Model Deployment

The model is deployed using Streamlit, providing an interactive web interface for users to input transaction details and receive predictions.

Setup

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/fraud-detection.git
cd fraud-detection
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Streamlit web application locally:
bash
Copy code
streamlit run final_app/Home.py
Open your browser and go to http://localhost:8501 to view the deployed fraud detection app.

