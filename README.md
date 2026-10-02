# Forest Fire FWI Prediction 🔥

A Machine Learning web application that predicts the **Fire Weather Index (FWI)** based on weather and environmental conditions.

The trained Machine Learning model is integrated with a **Flask web application**, allowing users to enter weather parameters through a web interface and get an FWI prediction.

## 📌 Project Overview

This project uses Machine Learning to predict the Fire Weather Index (FWI) from different weather and environmental features.

The project includes:

- Data preprocessing
- Feature scaling using StandardScaler
- Ridge Regression model
- Model training and evaluation
- Flask web application
- HTML-based user interface
- Model and scaler saved using Pickle

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- Matplotlib
- Jupyter Notebook
- HTML/CSS

## 📂 Project Structure

```text
Project/
│
├── dataset/
│   └── Algerian_forest_fires_dataset.csv
│
├── models/
│   ├── ridge.pkl
│   └── scaler.pkl
│
├── notebooks/
│   ├── Algerian_forest_fires_dataset.csv
│   ├── Model_Training.ipynb
│   └── RidgeLasso_Regression.ipynb
│
├── templates/
│   ├── home.html
│   └── index.html
│
├── application.py
├── requirements.txt
├── README.md
└── .gitignore