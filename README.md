# MPG Prediction using Neural Networks and Tableau

This project predicts the fuel efficiency (MPG) of cars using a neural network model and visualizes the results in Tableau.

## Project Overview

The goal of this project is to:
- Build a neural network regression model
- Predict MPG values using car specifications
- Export predictions for visualization in Tableau
- Build an interactive analytics dashboard

## Dataset

Dataset: Auto MPG dataset

Features used:
- Cylinders
- Displacement
- Horsepower
- Weight
- Acceleration
- Model Year
- Origin

Additional engineered features:
- Power to weight ratio
- Engine efficiency factor

## Machine Learning Model

Model: Neural Network (TensorFlow/Keras)

Architecture:
Input Layer → Dense(64) → Dense(64) → Output Layer

Loss Function: Mean Squared Error

## Project Structure

mpg-neural-network-dashboard
│
├── auto_mpg.csv
├── mpg_predictions.csv
├── mpg_prediction_model.ipynb
├── README.md

## Technologies Used

Python
TensorFlow / Keras
Scikit-learn
Pandas
Tableau

## Tableau Dashboard

![Dashboard](images/dashboard.png)

