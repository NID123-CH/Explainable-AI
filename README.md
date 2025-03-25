# Explainable AI for Heart Disease Dataset

# Overview

This repository provides an Explainable AI (XAI) approach to analyzing heart disease data. The goal is to build machine learning models that can predict heart disease while offering human-interpretable explanations for the predictions.

# Features

## Machine Learning Models: Implement multiple ML models (Logistic Regression, Random Forest, XGBoost, etc.)

## Explainability Techniques: Use SHAP (SHapley Additive Explanations), LIME (Local Interpretable Model-agnostic Explanations), and Feature Importance methods

## Data Visualization: Provide insightful plots to understand feature contributions

## Interactive Dashboard: Develop a web-based dashboard for real-time model interpretation

# Dataset

The dataset used is the UCI Heart Disease Dataset, which contains medical records of patients with various health parameters. It can be accessed from the UCI Machine Learning Repository.

# Data Features

The dataset includes the following features:

Age, Sex, Chest Pain Type (CP)

Resting Blood Pressure (trestbps), Cholesterol (chol)

Fasting Blood Sugar (fbs), Resting ECG (restecg)

Maximum Heart Rate (thalach), Exercise-induced Angina (exang)

Oldpeak (ST depression), Slope of ST segment, Number of Major Vessels

Thalassemia, and Target (presence or absence of heart disease)

# Installation

Clone the repository:

git clone https://github.com/your-username/XAI-Heart-Disease.git
cd XAI-Heart-Disease

Install required dependencies:

pip install -r requirements.txt

Usage

# Preprocess Data:

python preprocess.py

# Train Models:

python train.py

# Generate Explanations:

python explain.py

# Run Dashboard:

streamlit run dashboard.py

Model Explainability

SHAP

SHAP values help in understanding the contribution of each feature towards a model's prediction.

LIME

LIME provides local interpretability by approximating complex models with simpler, explainable ones.

# Feature Importance

Feature importance scores indicate which features have the most impact on predictions.

Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

# License

This project is licensed under the MIT License.

# Acknowledgments

UCI Machine Learning Repository for providing the dataset

SHAP and LIME libraries for model explainability

Scikit-learn, Pandas, Matplotlib for ML and visualization
