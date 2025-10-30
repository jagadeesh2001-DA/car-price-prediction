🚗 Car Price Prediction Using Linear Regression
📘 Overview

This project predicts the selling price of used cars based on various features like brand, age, mileage, fuel type, and power using Linear Regression. The goal is to help estimate fair market prices and support decision-making for car buyers and sellers.

✨ Features

✅ Data Cleaning: Handles missing values, removes units (e.g., "km", "CC") from numeric columns, and encodes categorical data.
✅ Feature Engineering: Adds derived features like power_per_CC and encodes model names.
✅ Model Training: Implements a Linear Regression model to predict car prices.
✅ Scaling: Uses StandardScaler to normalize feature values.
✅ Evaluation: Measures model performance using R² Score, MAE, and RMSE.


⚙️ Installation

Clone this repository:
git clone https://github.com/your-username/Car_Price_Prediction.git
cd Car_Price_Prediction

Install required dependencies: pip install -r requirements.txt

🚀 Usage

Run the Jupyter Notebook to train and test the model:
jupyter notebook Linear_Regression.ipynb

🧠 Dataset

Source: Kaggle / Custom Car Dataset
Features Used:

brand
vehicle_age
km_driven
seller_type
fuel_type
transmission_type
mileage_kmpl
max_power
seats
power_per_CC
model_encoded

Target Variable:
selling_price

🧩 Model Details
Algorithm Used: Linear Regression
Feature Scaling: StandardScaler
Train-Test Split: 80%-20%

📊 Evaluation Metrics
R² Score: Measures how well the model fits the data
MAE (Mean Absolute Error): Average of absolute prediction errors
RMSE (Root Mean Squared Error): Penalizes large errors

📈 Results & Visualization
Includes visual analysis of:
Price vs. Age
Price vs. Power
Feature correlation heatmap
Actual vs. Predicted price comparison
