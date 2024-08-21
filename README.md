# House Price Prediction

This project is a simple machine learning model that predicts house prices based on the size of the house using a linear function. The model uses a single feature, `size of the house (in square feet)`, to make predictions.

## Project Overview

The goal of this project is to demonstrate how a basic linear regression model can be used to predict house prices. Given the size of a house, the model predicts the corresponding price using a linear relationship.

## Features

- **Size of the House (in square feet):** The only input feature used to predict the price of a house.

## Model

The model is a simple linear regression model that fits a straight line to the data, representing the relationship between the size of the house and its price.

The linear function used for prediction is:
Price = w * Size + b

where:
- `w` is the slope of the line (i.e., the coefficient)
- `b` is the y-intercept

## Dataset

The dataset used in this project consists of house sizes (in square feet) and their corresponding prices. The data was generated for educational purposes and represents a simple linear relationship between the size of the house and its price.

## Installation and Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt


# Example usage
size_of_house = 1500  # square feet
predicted_price = model.predict(size_of_house)
print(f"The predicted price for a house of {size_of_house} square feet is ${predicted_price:.2f}")
