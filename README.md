Fraud Detection System (Logistic Regression)
Overview

This project implements a fraud detection model using Logistic Regression on a large-scale financial transaction dataset. The goal is to identify fraudulent transactions in highly imbalanced data while minimizing missed fraud cases. The trained model is deployed as an interactive Streamlit web application for real-time predictions.

Dataset

Source: Kaggle – Fraud Detection Dataset

Total transactions: 6.3M+

Fraud rate: ~0.13%

Model evaluated on a 1.9M transaction test set

Approach

Performed data preprocessing and feature selection

Trained a Logistic Regression model using scikit-learn

Evaluated performance using accuracy, precision, recall, F1-score, and confusion matrix

Integrated the trained model into a Streamlit app for real-time fraud prediction

Results

93% model accuracy on the test set

Correctly identified 2,289 fraudulent transactions

Demonstrated scalable fraud detection on large datasets

Tech Stack

Python, pandas, NumPy, scikit-learn, Streamlit, joblib
