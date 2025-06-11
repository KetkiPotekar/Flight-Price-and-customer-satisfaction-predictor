✈️ Flight Ticket Price Prediction & Customer Satisfaction Classification
🧠 Overview
This repository contains two end-to-end machine learning projects focused on solving real-world challenges in the travel and airline industry:

Flight Ticket Price Prediction (Regression)

Customer Satisfaction Prediction (Classification)

Each project includes data preprocessing, feature engineering, model training and evaluation, MLflow integration, and deployment using Streamlit.

📌 Project 1: Flight Ticket Price Prediction
📄 Problem Statement
Build a regression model to predict flight ticket prices based on features such as departure time, airline, source, destination, and route. Deploy the model using Streamlit to allow real-time user input and price predictions.

💼 Business Use Cases
Help travelers estimate flight prices based on preferences.

Assist travel agencies with pricing strategy and planning.

Enable businesses to forecast travel expenses.

Support airlines in dynamic pricing and trend analysis.

🛠 Approach
Data Preprocessing

Load and clean the dataset.

Handle missing/duplicate values.

Convert and engineer time-related features.

Create derived features like duration in minutes, day/month of journey, etc.

Model Training

Perform Exploratory Data Analysis (EDA).

Train regression models: Linear Regression, Random Forest, XGBoost.

Use metrics like RMSE, MAE, and R² for evaluation.

MLflow Integration

Log experiments, parameters, metrics, and model artifacts.

Organize models in MLflow Model Registry.

Streamlit Deployment

Interactive app to visualize trends and predict prices.

User inputs: Source, Destination, Date, Airline, Stops, etc.

📊 Results
Cleaned and enriched dataset for analysis.

Accurate price predictions using ensemble models.

Fully functional Streamlit dashboard with MLflow-tracked models.

🧪 Evaluation Metrics
RMSE (Root Mean Squared Error)

R² Score

Model tracking with MLflow
