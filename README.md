#Hybrid-Approach-for-Early-stage-detection-of-autism
🧠 Early Detection of Autism Spectrum Disorder (ML-Based Tool)

📌 Project Overview

This project focuses on the early-stage detection of Autism Spectrum Disorder (ASD) using machine learning techniques. It provides an end-to-end Python-based pipeline that includes data preprocessing, feature extraction, model training, evaluation, and real-time prediction through a Streamlit web application.

The goal is to assist in early screening by comparing multiple ML models and identifying the most reliable approach.

🚀 Key Features

End-to-end machine learning pipeline

Automated model comparison

Multiple ML algorithms implemented

Real-time prediction using Streamlit

Detailed model evaluation and failure analysis

Easy-to-use internal web interface

🛠️ Technologies Used

Programming Language: Python

Machine Learning Models:

Support Vector Machine (SVM)

Random Forest

XGBoost

CatBoost

Libraries & Tools:

NumPy

Pandas

Scikit-learn

XGBoost

CatBoost

Matplotlib / Seaborn

Streamlit

📂 Project Structure
Hybrid-Approach-for-Early-stage-detection-of-autism/
│
├── data/                   # Dataset files
├── notebooks/              # Jupyter notebooks for experiments
├── models/                 # Trained models
├── app.py                  # Streamlit application
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation

⚙️ Workflow

Data Collection & Preprocessing

Handling missing values

Encoding categorical features

Feature scaling

Feature Extraction

Selection of relevant behavioral and demographic features

Model Training

Training SVM, Random Forest, XGBoost, and CatBoost models

Model Evaluation

Accuracy, Precision, Recall, F1-score

Confusion Matrix analysis

Failure Analysis

Analysis of misclassified samples

Model performance debugging

Deployment

Streamlit-based real-time prediction interface

📊 Model Evaluation

The models were evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

A comparative analysis was performed to identify the best-performing model for ASD prediction.

🖥️ Streamlit Application

The Streamlit app allows users to:

Enter input features interactively

Get real-time ASD prediction

Visualize model output and confidence

▶️ Run the App
streamlit run app.py

📦 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/dhanyasanagapalli/Hybrid-Approach-for-Early-stage-detection-of-autism.git
cd Hybrid-Approach-for-Early-stage-detection-of-autism

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Project

For training & evaluation: use notebooks or scripts

For UI: run the Streamlit app

🎯 Use Cases

Early ASD screening support

Academic and research purposes

ML model comparison studies

Healthcare decision-support systems (non-diagnostic)

⚠️ Disclaimer

This tool is intended for research and educational purposes only.
It is not a medical diagnostic system and should not replace professional clinical evaluation.

👩‍💻 Author

Dhanya Sanagapalli
🔗 GitHub: https://github.com/dhanyasanagapalli

⭐ If you like this project

Don’t forget to star ⭐ the repository and share feedback!
