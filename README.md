# House Price Prediction

A beginner-level machine learning project that predicts California house prices using Linear Regression.

## Project Overview

This project demonstrates the basic machine learning workflow:

1. Load the dataset
2. Perform Exploratory Data Analysis (EDA)
3. Identify features and target
4. Split the data into training and testing sets
5. Train a Linear Regression model
6. Generate predictions
7. Evaluate the model
8. Analyze residuals
9. Save the trained model

## Dataset

The project uses the California Housing dataset available through Scikit-learn.

### Features

- MedInc - Median income
- HouseAge - Median house age
- AveRooms - Average number of rooms
- AveBedrms - Average number of bedrooms
- Population - Block population
- AveOccup - Average house occupancy
- Latitude - Geographic latitude
- Longitude - Geographic longitude

### Target

`MedHouseVal` - Median house value

## Model

The model used is:

**Linear Regression**

## Results

| Metric | Value |
|---|---:|
| MAE | 0.5332 |
| MSE | 0.5559 |
| RMSE | 0.7456 |
| R² | 0.5758 |

## Model Interpretation

The Linear Regression model captures a meaningful relationship between the input features and house prices.

The residual analysis shows that the model still has substantial errors for some observations, indicating that a simple linear model cannot capture all relationships in the dataset.

## Project Structure

```text
house-price-prediction/
│
├── data/
├── models/
│   └── linear_regression_model.pkl
├── notebooks/
│   └── 01_eda.ipynb
├── src/
├── .gitignore
└── README.md