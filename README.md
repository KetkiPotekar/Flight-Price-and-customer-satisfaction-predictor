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

🛠 Approach <br/>
Data Preprocessing <br/>
Load and clean the dataset. <br/>
Handle missing/duplicate values. <br/>
Convert and engineer time-related features. <br/>
Create derived features like duration in minutes, day/month of journey, etc. <br/>


Model Training <br/>
Perform Exploratory Data Analysis (EDA). <br/>
Train regression models: Linear Regression, Random Forest, XGBoost. <br/>
Use metrics like RMSE, MAE, and R² for evaluation. <br/>


MLflow Integration <br/>
Log experiments, parameters, metrics, and model artifacts. <br/>
Organize models in MLflow Model Registry. <br/>


Streamlit Deployment <br/>
Interactive app to visualize trends and predict prices. <br/>
User inputs: Source, Destination, Date, Airline, Stops, etc. <br/>


📊 Results <br/>
Cleaned and enriched dataset for analysis.<br/>
Accurate price predictions using ensemble models.<br/>
Fully functional Streamlit dashboard with MLflow-tracked models.<br/>

🧪 Evaluation Metrics<br/>
RMSE (Root Mean Squared Error)<br/>
R² Score<br/>
Model tracking with MLflow<br/>


📌 Project 2: Customer Satisfaction Prediction<br/>
📄 Problem Statement <br/>
Build a classification model to predict airline customer satisfaction based on demographics, travel class, service ratings, and delays. The model is deployed with Streamlit for real-time satisfaction prediction based on user input.<br/>

💼 Business Use Cases <br/>
Enhance customer experience and retention. <br/>
Drive service improvements through predictive insights. <br/>
Assist marketing teams in targeting specific customer groups. <br/>
Enable data-driven management decisions.

🛠 Approach <br/>
Data Preprocessing <br/>
Clean missing and duplicate data. <br/>
Encode categorical features. <br/>
Normalize numerical columns. <br/>

Model Training <br/>
EDA to explore feature correlations. <br/>
Train classifiers: Logistic Regression, Random Forest, Gradient Boosting. <br/>
Use metrics like Accuracy, F1-Score, and Confusion Matrix for evaluation. <br/>

MLflow Integration <br/>
Log all models, parameters, and metrics. <br/>
Track confusion matrices and F1 scores.<br/>

Streamlit Deployment<br/>
Input form for users to enter demographic and service data. <br/>
Predict and display satisfaction status.<br/>
Visualizations of trends and insights.<br/>

📊 Results <br/>
Efficient preprocessing and feature engineering. <br/>
High-accuracy satisfaction prediction models. <br/>
Streamlit app with intuitive interface and MLflow integration. <br/>

🧪 Evaluation Metrics <br/>
Accuracy <br/>
F1-Score <br/>
Confusion Matrix <br/>
