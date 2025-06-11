✈️ Flight Ticket Price Prediction & Customer Satisfaction Classification <br/>

🧠 Overview <br/>
This repository contains two end-to-end machine learning projects focused on solving real-world challenges in the travel and airline industry: <br/>
Flight Ticket Price Prediction (Regression) <br/>
Customer Satisfaction Prediction (Classification)<br/>

Each project includes data preprocessing, feature engineering, model training and evaluation, MLflow integration, and deployment using Streamlit. <br/>


📌 Project 1: Flight Ticket Price Prediction<br/>
📄 Problem Statement<br/>
Build a regression model to predict flight ticket prices based on features such as departure time, airline, source, destination, and route. Deploy the model using Streamlit to allow real-time user input and price predictions.<br/>

💼 Business Use Cases <br/>
Help travelers estimate flight prices based on preferences. <br/>
Assist travel agencies with pricing strategy and planning. <br/>
Enable businesses to forecast travel expenses. <br/>
Support airlines in dynamic pricing and trend analysis. <br/>

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


📌 Project 2: Customer Satisfaction Prediction
📄 Problem Statement
Build a classification model to predict airline customer satisfaction based on demographics, travel class, service ratings, and delays. The model is deployed with Streamlit for real-time satisfaction prediction based on user input.

💼 Business Use Cases
Enhance customer experience and retention.
Drive service improvements through predictive insights.
Assist marketing teams in targeting specific customer groups.
Enable data-driven management decisions.

🛠 Approach
Data Preprocessing
Clean missing and duplicate data.
Encode categorical features.
Normalize numerical columns.

Model Training
EDA to explore feature correlations.
Train classifiers: Logistic Regression, Random Forest, Gradient Boosting.
Use metrics like Accuracy, F1-Score, and Confusion Matrix for evaluation.

MLflow Integration
Log all models, parameters, and metrics.
Track confusion matrices and F1 scores.

Streamlit Deployment
Input form for users to enter demographic and service data.
Predict and display satisfaction status.
Visualizations of trends and insights.

📊 Results
Efficient preprocessing and feature engineering.
High-accuracy satisfaction prediction models.
Streamlit app with intuitive interface and MLflow integration.

🧪 Evaluation Metrics
Accuracy
F1-Score
Confusion Matrix
