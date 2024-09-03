# Stock Market Prediction Project

This repository contains the code and documentation for a project aimed at predicting stock prices for major companies like AAPL, GOOGL, and MSFT using various machine learning models. The project explores traditional models like Linear Regression and Support Vector Regressor, as well as deep learning models like LSTM, GRU, and CNN.

## Project Overview

The objective of this project is to analyze historical stock data and predict future opening and closing prices. We evaluate different models to determine the best approach for accurate stock price prediction.

## Features

- **Data Preprocessing:** Handling missing values, outliers, and splitting the dataset into training and testing sets.
- **Model Training:** Training and fine-tuning multiple machine learning models.
- **Model Evaluation:** Comparing models based on metrics like accuracy, precision, recall, and F1 score.
- **Visualization:** Generating plots to visualize stock trends and model performance.

## Installation

To run the project, ensure you have Python installed along with the required libraries. You can install the dependencies using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow keras
## Usage

### Clone the Repository:

```bash
git clone https://github.com/yourusername/stock-market-prediction.git
### Run the Jupyter Notebook:

Open `stock_market_prediction.ipynb` and `stock_market_prediction_with_deep_leaning_models.ipynb` in Google Colab or Jupyter Notebook and execute the cells to preprocess data, train models, and visualize results.

## Input Data

The project uses historical stock data in CSV format with the following columns:

- **Date:** The date of the stock price.
- **Open:** The opening price.
- **Close:** The closing price.
- **Volume:** The volume of stocks traded.
- **High:** The highest price during the day.
- **Low:** The lowest price during the day.

## Output Data

The output includes:

- Predicted opening and closing prices.
- Performance metrics (accuracy, precision, recall, F1 score).
- Plots showing stock trends and model performance.

## Key Models

- **Linear Regression**
- **Support Vector Regressor (SVR)**
- **Gradient Boosting Regressor**
- **LSTM**
- **GRU**
- **CNN**

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.
