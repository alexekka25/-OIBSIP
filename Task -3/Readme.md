# Car Price Prediction Model

This repository contains the code and instructions for building a car price prediction model using machine learning. The model is trained to predict the selling price of cars based on various features and is saved for future use.

## Table of Contents
> Introduction

> Requirements

> Data

> Model Training

> Model Saving


# Introduction
This project involves predicting car prices using a Random Forest model. The model is trained on a dataset with features such as present price, driven kilometers, car age, fuel type, and more. The final model is saved and can be loaded for predictions.

# Requirements
Before running the code, ensure you have the following Python packages installed:

> numpy

> pandas

> scikit-learn

> joblib

# Data
The dataset used for training the model contains the following columns:

- [Car_Name](#overview)
- [Year](#Year)
- [Selling_Price](#Selling_Price)
- [Present_Price](#Present_Price)
- [Driven_kms](#Driven_kms)
- [Fuel_Type](#Fuel_Type)
- [Selling_type](#Selling_type)
- [Transmission](#Transmission)
- [Owner](#Owner)

  -The data preprocessing steps include-

Handling categorical features through one-hot encoding.
Standardizing numerical features.

# Model Training

The model is trained using the Random Forest Regressor from scikit-learn. Here’s a brief overview of the training process:

1.Load Data: Import and preprocess the dataset.
2.Split Data: Divide the data into training and testing sets.
3.Train Model: Use Random Forest Regressor for training.
4.Evaluate Model: Assess the model performance using RMSE and R² score.

# Model Saving
The trained model is saved using joblib. The model file is named random_forest_car_price_model.pkl and can be loaded for making predictions in the future.
