# Dynamic Product Price Predictor

## Description

This project implements a **Dynamic Product Price Predictor** using a machine learning model to predict the final price of products based on their attributes, such as product rating, discount percentage, brand, and category. The prediction is made using an **XGBoost** model, and the app is deployed with **Streamlit** for user interaction and **ngrok** for remote access.

## Features

- **User Input**: 
  - Product Rating (0.0 to 5.0)
  - Discount Percentage (0 to 100%)
  - Brand (Encoded Value)
  - Category (Encoded Value)
  
- **Prediction Output**: 
  - The app predicts the final price of a product based on the given inputs.
  
- **Deployed Application**:
  - Exposed via **ngrok** to allow external access to the app.

## Requirements

To run this project locally or deploy it, you need to have the following libraries installed:

- `streamlit`
- `joblib`
- `numpy`
- `pyngrok`
- `xgboost` (for the model)

You can install the required libraries using the following command:

```bash
pip install streamlit joblib numpy pyngrok xgboost
