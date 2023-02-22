# AI Trading Bot Project
This project uses machine learning and deep learning techniques to create a trading bot that can make predictions about the stock market and generate profits. In this project, we use a dataset of historical stock prices to train machine learning models and make predictions about future stock prices. We then use these predictions to make buy and sell decisions in order to generate profits.

## Getting Started
### Prerequisites
This project requires the following tools and packages:

* Python 3.7 or higher
* Jupyter Notebook
* Pandas
* NumPy
* scikit-learn
* tensorflow
* keras
* matplotlib

## Installing
You can install the required packages using pip.

pip install pandas numpy scikit-learn tensorflow keras matplotlib

## Data
The data used in this project consists of historical stock prices for several companies. The data was obtained from Yahoo Finance and contains the following columns:

* Date: The date of the stock price.
* Open: The opening stock price for the day.
* High: The highest stock price for the day.
* Low: The lowest stock price for the day.
* Close: The closing stock price for the day.
* Adj Close: The adjusted closing stock price for the day.
* Volume: The volume of stocks traded for the day.

## Machine Learning Models
In this project, we used several machine learning models to make predictions about the stock market. We trained the models using historical stock prices and used them to make predictions about future stock prices. The models we used include:

* Linear Regression
* Random Forest
* SVM
* AdaBoost

## Deep Learning Models
We also used deep learning models to make predictions about the stock market. We used a recurrent neural network (RNN) to make predictions based on the historical stock prices. The RNN was trained on sequences of historical stock prices and used to make predictions about future stock prices.

## Results
We evaluated the performance of each model using the following metrics:

* Accuracy
* Precision
* Recall
* F1-Score
We found that the AdaBoost model performed the best, with an accuracy of 0.60 and a precision of 0.60. The SVM model performed the worst, with an accuracy of 0.45 and a precision of 0.44.

We also backtested the AdaBoost model and found that it was able to generate profits, with a cumulative return of 16.07% over the test period. However, the strategy did not perform as well during certain market conditions, such as during the COVID-19 pandemic.

## Evaluation Report
Overall, we found that machine learning and deep learning models can be effective at predicting stock prices and generating profits. However, it is important to carefully evaluate the performance of each model and to consider the limitations of these models, such as their sensitivity to market conditions.

Based on our analysis, we recommend using the AdaBoost model for making stock market predictions and generating profits. However, we also recommend carefully monitoring the performance of the model and making adjustments as needed based on changing market conditions.



