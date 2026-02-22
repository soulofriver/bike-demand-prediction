Bike Sharing Demand Prediction - ANN

🚲 Bike Sharing Demand Prediction using an Artificial Neural Network (ANN) with a Tkinter GUI.

🔹 Project Overview

This project implements a neural network to predict bike rental demand in a bike-sharing system.
Key features:

Feature engineering for temporal and weather-related data

Multi-layer ANN with Dropout to prevent overfitting

Accurate demand predictions (RMSE, MAE, R²)

Simple Tkinter GUI for entering input data and viewing predictions

🔹 Features

Input data: Hour, Day, Month, Weekday, Season, Holiday, Working Day, Weather, Temperature, Feels-like Temperature, Humidity, and Windspeed

Preprocessing: StandardScaler for numeric features, One-Hot Encoding for categorical features

Output: Predicted bike demand

🔹 Dataset

This project uses the Bike Sharing Demand dataset on Kaggle
(https://www.kaggle.com/competitions/bike-sharing-demand/data)
Download train.csv and place it in the data/raw/ folder before running the program.
🔹 Installation

🔹 Model Evaluation

After training, the model is evaluated on the validation set:

RMSE: Root Mean Squared Error

MAE: Mean Absolute Error

R²: Coefficient of Determination

These metrics are printed in the console after training.

🔹 Using the GUI

Launch the program (python main.py)

Enter input values in the GUI fields: hour, day, month, weekday, season, holiday, working day, weather, temperature, feels-like temperature, humidity, and windspeed

Click “Predict” to see the predicted bike demand
