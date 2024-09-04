# Stock Price Prediction Using Machine Learning
This project is a machine learning model designed to predict the stock prices of 10 different companies. The model uses historical stock data and employs a Linear Regression algorithm to predict future stock prices. The dataset was sourced from Kaggle.
## Project Overview
* Goal: Predict the stock prices (close prices) for each company in the dataset based on historical data.
* Model: Linear Regression
* Dataset: https://www.kaggle.com/datasets/umerhaddii/top-10-global-companies-stock-data-2024/data
## Dataset
### Context
This dataset provides comprehensive stock market data for some of the world's leading companies, including Apple, Microsoft, Nvidia, Google, Amazon, Saudi Aramco, Meta, Berkshire Hathaway, TSMC, and Eli Lilly. It covers various financial metrics such as opening and closing prices, trading volumes, and market capitalization. The data spans across 2024, offering a valuable resource for analyzing market trends and investment strategies. Ideal for financial analysts, researchers, and data enthusiasts, this dataset enables in-depth analysis and forecasting. Utilize this data to explore stock performance and uncover market insights.

The dataset contains the following columns:

* Date: The date of the stock data entry.
* Ticker: The unique ticker symbol for the company.
* Open: The opening price of the stock on that date.
* High: The highest price of the stock on that date.
* Low: The lowest price of the stock on that date.
* Close: The closing price of the stock on that date,adjusted for splits.
* Adj Close: The adjusted closing price of the stock on that date.
* Volume: The number of shares traded on that date.
## Data Preparation Overview
In this project, the dataset includes historical stock data for 10 companies, with columns such as date, ticker symbol, and various stock prices. To build individual prediction models for each company, the dataset is first sliced by the ticker symbol. This process ensures that each model is trained on the specific data relevant to one company, allowing for more accurate and tailored predictions.
## Machine Learning Model
For this project, a separate Linear Regression model is trained for each company. After slicing the dataset by the ticker symbol, the relevant data for each company is used to train the model. The features include stock prices such as open, high, and low, while the target variable is the close price. This approach allows the model to learn the specific patterns and trends associated with each company's stock, leading to more precise predictions.
## Model Evaluation
The Linear Regression model was evaluated on its ability to predict the close price of stocks for each company. The model achieved a remarkable accuracy of 99%, demonstrating its effectiveness in capturing the underlying patterns in the stock data. This high level of accuracy indicates that the model is well-suited for making reliable stock price predictions.
## Project Summary
This project involved developing a Linear Regression model to predict stock prices for 11 different companies. The dataset, sourced from Kaggle, was preprocessed and sliced by ticker symbol to train individual models for each company. The features used for the prediction included the open, high, and low prices, with the close price as the target variable.

The model achieved an impressive accuracy of 99%, highlighting its ability to effectively capture and predict stock price movements. Specifically, the model can predict the close price of a stock on a trading day if given the open price and the high and low prices observed so far on that day.

This project not only demonstrates proficiency in data preparation and machine learning but also offers practical applications for financial forecasting and investment strategies. The project is publicly available on GitHub, allowing others to explore, replicate, and build upon the work.
