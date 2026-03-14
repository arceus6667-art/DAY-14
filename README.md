💳 Fraud Detection using PCA and Logistic Regression
📌 Overview

This project implements a Machine Learning based Fraud Detection System designed to identify suspicious financial transactions.

The model uses Principal Component Analysis (PCA) for dimensionality reduction and Logistic Regression for classification.

Additionally, the project includes Exploratory Data Analysis (EDA) and interactive visualizations to better understand transaction patterns.

This project was built as part of my 50 Days Machine Learning Challenge (Day 14).

🎯 Objectives

Detect fraudulent transactions using machine learning

Reduce high-dimensional financial data using PCA

Build a classification model for fraud detection

Perform detailed Exploratory Data Analysis

Create interactive 3D visualizations

🧠 Machine Learning Workflow

1️⃣ Data Loading
2️⃣ Data Cleaning and Preprocessing
3️⃣ Feature Scaling
4️⃣ Dimensionality Reduction using PCA
5️⃣ Model Training using Logistic Regression
6️⃣ Model Evaluation
7️⃣ Exploratory Data Analysis & Visualization

📊 Exploratory Data Analysis

The following visualizations were created:

• Correlation Heatmap
• Feature Distribution Histograms
• PCA Scatter Plots
• Fraud vs Non-Fraud Distribution
• Interactive 3D PCA Visualization using Plotly

These visualizations help reveal patterns between legitimate and fraudulent transactions.

🛠 Tech Stack

Python

Pandas

NumPy

Scikit-Learn

Plotly

Matplotlib

Seaborn

JupyterLab

📈 Model Used
Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for binary classification problems, making it suitable for detecting fraudulent transactions.

The model learns patterns from the PCA-transformed dataset and predicts whether a transaction is fraudulent or legitimate.

📂 Project Structure
fraud-detection-ml
│
├── data
│   └── dataset.csv
│
├── notebooks
│   └── fraud_detection_analysis.ipynb
│
├── visualizations
│   ├── heatmap.png
│   ├── histogram.png
│   └── pca_scatter.png
│
├── model
│   └── logistic_regression_model.pkl
│
└── README.md
🚀 How to Run the Project

Clone the repository

git clone YOUR_REPO_LINK

Navigate to the project folder

cd fraud-detection-ml

Install dependencies

pip install -r requirements.txt

Run the notebook

jupyter lab
📊 Results

The model successfully learns patterns between fraudulent and normal transactions and visualizations help reveal hidden insights in the data.
