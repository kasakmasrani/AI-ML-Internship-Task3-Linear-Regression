Linear Regression

This repository contains the implementation of simple and multiple linear regression models for house price prediction.

## Dataset
The dataset contains housing price information with the following features:
- price: Target variable (price in local currency)
- area: Area in square feet
- bedrooms: Number of bedrooms
- bathrooms: Number of bathrooms
- stories: Number of stories
- mainroad: Whether connected to main road (binary)
- guestroom: Whether has guest room (binary)
- basement: Whether has basement (binary)
- hotwaterheating: Whether has hot water heating (binary)
- airconditioning: Whether has air conditioning (binary)
- parking: Number of parking spaces
- prefarea: Whether is in preferred area (binary)
- furnishingstatus: Furnishing status (categorical)

## Implementation
1. **Simple Linear Regression**: Price vs Area
2. **Multiple Linear Regression**: Price vs all other features

## Evaluation Metrics
For each model, we calculate:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

## How to Run
1. Clone this repository
2. Install requirements: `pip install pandas numpy matplotlib scikit-learn`
3. Open and run `task.ipynb` in Jupyter Notebook

## Results
The notebook includes visualizations of the simple linear regression model and interpretation of coefficients for the multiple regression model.
