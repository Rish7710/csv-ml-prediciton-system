📊 CSV ML Prediction System

A complete Machine Learning pipeline project that trains a model using CSV data, saves it as a pipeline, and provides predictions through a Streamlit web app.

This project demonstrates:

Data loading from CSV

ML pipeline creation

Model training & saving

Model inference

Streamlit-based UI

🚀 Project Overview

This system predicts whether a student will pass or fail based on:

Study hours

Attendance percentage

The ML workflow is automated using scikit-learn Pipelines and the trained model is saved using joblib.

📁 Project Structure
csv-ml-prediction-system/
│
├── data/
│   └── train.csv          # Training dataset
│
├── pipeline.py            # Model training & saving
├── model.pkl              # Saved ML pipeline (generated after training)
├── streamlit_app.py       # Streamlit web application
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation

🧠 Machine Learning Details

Model: Logistic Regression

Preprocessing: StandardScaler

Pipeline: Scaler + Model

Target column: pass

Features: hours, attendance

Using a pipeline ensures consistent preprocessing during training and prediction.

📦 Requirements

Install dependencies using:

pip install -r requirements.txt

requirements.txt
pandas
numpy
scikit-learn
joblib
streamlit

⚙️ How to Train the Model

Run the training pipeline:

python pipeline.py

Output:
Model Trained and Saved


This will create:

model.pkl



📈 Future Improvements

Add model evaluation metrics

Support more features

Deploy on Streamlit Cloud

Add REST API support

👨‍💻 Author

Built as part of a Day-by-Day ML Learning Journey
Focused on real-world, production-ready ML projects 🚀


✔️ Write a project description for Upwork/Fiverr

Just tell me 👍
