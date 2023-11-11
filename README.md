# OLS Algorithm for MacBook Price Prediction

## Overview
This Jupyter notebook showcases the creation of an Ordinary Least Squares (OLS) regression algorithm from scratch using Pandas and NumPy. The project focuses on predicting the prices of Apple MacBooks using a small dataset.

## Key Features
- **Custom OLS Implementation:** Development of an OLS regression model without conventional machine learning libraries, utilizing only Pandas and NumPy.
- **Apple MacBook Dataset:** Application of a dataset featuring 16 rows of various Apple MacBook models, including their specifications and prices.
- **Performance Metrics:** Model evaluation using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

## Contents
- `OLS.ipynb` - The primary Jupyter notebook containing the algorithm and its documentation.
- `amazon_laptop_prices_v01.csv` - Directory containing the dataset used for the project.
- `requirements.txt` - A list of Python packages required to run the notebook.

## Getting Started
To run this project:
1. Clone the repository to your local machine.
2. Install the necessary dependencies: `pip install -r requirements.txt`.
3. Launch the Jupyter notebook and execute the cells to see the algorithm in action.

## Methodology
- **Data Preprocessing:** Initial cleaning and preparation of the data for the OLS model.
- **Algorithm Implementation:** Step-by-step implementation of the OLS algorithm, with documentation.
- **Model Evaluation:** Assessing the model's performance using MAE, MSE, and RMSE, and discussing the outcomes.

## Results
- The custom OLS model achieved the following metrics on the MacBook dataset:
  - MAE: 165.32
  - MSE: 48442.31
  - RMSE: 220.10
- These metrics suggest potential areas for improvement and the impact of limited dataset size on model accuracy.

## Future Work
- **Dataset Expansion:** Enlarging the dataset size could enhance model performance.
- **Model Refinement:** Implementing more sophisticated techniques or fine-tuning the existing algorithm for better accuracy.
- **Data Splitting:** Segregating the dataset into training and testing sets for a more accurate evaluation of the model.

