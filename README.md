# House Price Prediction Using Machine Learning

A machine learning project that predicts residential house sale prices from property features using Python and Scikit-learn.

## Project Objective

The goal of this project is to build and evaluate regression models that predict house prices based on property characteristics such as area, quality, age, bathrooms, and location.

## Workflow

- Loaded and explored the housing dataset
- Checked missing values and duplicate rows
- Analyzed price distribution and feature correlations
- Created engineered features such as total area, total bathrooms, house age, and remodel age
- Used leakage-safe preprocessing pipelines
- Applied median imputation for numerical features
- Applied most-frequent imputation and one-hot encoding for categorical features
- Split data into training and testing sets
- Compared multiple regression models
- Evaluated models using MAE, RMSE, R2, and cross-validation
- Visualized actual versus predicted prices, residuals, and feature importance

## Models Used

- Linear Regression
- Support Vector Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Files

- `housing_prices_project.ipynb` — Complete analysis and modeling notebook
- `HousePricePrediction.xlsx` — Housing dataset

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload or place `HousePricePrediction.xlsx` in the required location.
3. Run all cells in order.

## Author

Himansi
