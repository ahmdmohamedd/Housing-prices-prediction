# Housing Price Prediction

## Overview
This project aims to predict housing prices using a feedforward neural network. By analyzing various housing attributes such as size, number of rooms, and location, the model learns complex relationships between these features and the prices of the houses. The effectiveness of the model is evaluated using metrics such as Mean Absolute Error (MAE) and R² score.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Contributing](#contributing)

## Features
- Predict housing prices based on various features
- Use of feedforward neural network for regression
- Evaluation metrics to assess model performance

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Dataset
The dataset used in this project is a housing dataset containing various attributes of houses. You can find it [here](link_to_dataset). It includes features such as:
- Size (square feet)
- Number of bedrooms
- Number of bathrooms
- Location
- Age of the house
- Price (target variable)

## Installation
Clone this repository:
   ```bash
   git clone https://github.com/ahmdmohamedd/Housing-prices-prediction.git
   cd Housing-prices-prediction
   ```

## Usage
1. Load the Jupyter notebook:
   ```bash
   jupyter notebook price_prediction.ipynb
   ```

2. Run the cells in the notebook to preprocess the data, train the model, and visualize the results.

## Evaluation Metrics
The model performance is evaluated using the following metrics:
- **Mean Absolute Error (MAE)**: Measures the average absolute difference between predicted and actual prices.
- **Mean Squared Error (MSE)**: Measures the average of the squares of the errors.
- **R² Score**: Indicates the proportion of variance in the target variable that is predictable from the features.

## Results
The model achieved the following evaluation metrics:
- Mean Absolute Error (MAE): 2.98
- Mean Squared Error (MSE): 24.18
- R² Score: 0.71

These results indicate a reasonably good fit for predicting housing prices.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.
