# Customer-Churn-Prediction
An end-to-end ML pipeline predicting telco customer churn. Features SMOTE for imbalanced data, Random Forest classification, and SHAP for model explainability. Deployed as a microservice using a FastAPI backend, an interactive Streamlit dashboard, Docker, and Google Cloud Run.
Customer retention is critical for subscription-based services. This repository contains a complete workflow for predicting which customers are at risk of leaving. It handles data preprocessing, class imbalance, model training, and serves predictions through a REST API connected to an interactive frontend.

** ✨ Key Features

Exploratory Data Analysis (EDA): Visualized feature distributions and correlations across 7,000+ customer records using Matplotlib and Seaborn.

Robust Data Preprocessing: Handled significant class imbalances (5,174 retained vs. 1,869 churned) using SMOTE to ensure unbiased model training.

Predictive Modeling: Evaluated multiple classification algorithms including Logistic Regression, Decision Trees, and Random Forest, optimized for ROC-AUC.

Model Explainability: Integrated SHAP (SHapley Additive exPlanations) to generate global feature importance charts and local waterfall plots, explaining exactly why a specific customer is flagged as a churn risk.

Microservices Architecture: Decoupled the backend machine learning model from the frontend interface using a FastAPI backend.

Interactive Dashboard: Built a user-friendly Streamlit web application for real-time inference and data exploration.

Containerization & Deployment: Fully containerized the application using Docker and configured for seamless deployment on Google Cloud Run.


** 🛠️ Tech Stack

Machine Learning & Data Processing: Python, Scikit-learn, Imbalanced-learn (SMOTE), Pandas, NumPy

Visualization & Explainability: SHAP, Matplotlib, Seaborn

Backend API: FastAPI

Frontend Web App: Streamlit

DevOps & Cloud: Docker, Git/GitHub, Google Cloud Run
