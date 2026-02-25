# Energy-Consumption-Prediction
📌 Project Overview

This project aims to predict household appliance energy consumption using environmental and usage-related features. The dataset contains temperature, humidity, lighting, and weather-related variables that influence energy usage.

The objective is to build and compare different regression models to determine which model best predicts energy consumption.

📊 Dataset Information

Dataset Name: Appliances Energy Prediction

Total Records: 19,735

Total Features: 29

Target Variable: Appliances (Energy Consumption in Wh)

🔹 Feature Categories:

Indoor Temperature (T1 – T9)

Humidity (RH_1 – RH_9)

Outdoor Temperature (T_out)

Pressure (Press_mm_hg)

Wind Speed

Visibility

Lights

Date (removed during preprocessing)

🛠 Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

🔄 Project Workflow

Data Loading

Data Cleaning (Removed date column)

Feature Selection

Train-Test Split

Model Training

Model Evaluation

🤖 Models Implemented

The following regression models were used:

Linear Regression

K-Nearest Neighbors (KNN)

Decision Tree Regressor

Random Forest Regressor

📈 Model Performance Comparison
Model	R² Score	MSE
Linear Regression	0.167	8579
KNN	0.168	8569
Decision Tree	0.146	8792
Random Forest	0.510	5041
🏆 Best Model

Random Forest achieved the highest R² score (0.51) and lowest MSE, indicating better prediction accuracy.

This suggests that energy consumption has nonlinear relationships with environmental features, and ensemble models perform better for such complex data.
