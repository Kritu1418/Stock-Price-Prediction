# Stock-Price-Prediction

AIM : TO PREDICT THE STOCK PRICE OF A COMPANY USING LSTM.
DATASET INFORMATION:
GOOGLE STOCK PREDICTION
This dataset comprises historical data related to Google's stock prices and various associated attributes. It contains 14 columns and a smaller subset of 1257 rows. Each column represents a specific attribute, and each row contains the corresponding values for that attribute.

The columns in the dataset are as follows:

Company Symbol: Represents the name of the company, which, in this case, is GOOG for Google.
Date: Indicates the year and date of the stock data.
Close: Denotes the closing price of Google's stock on a particular day.
High: Represents the highest value reached by Google's stock on the given day.
Low: Represents the lowest value reached by Google's stock on the given day.
Open: Indicates the opening value of Google's stock on the given day.
Volume: Represents the trading volume of Google's stock on the given day, i.e., the number of shares traded.
Adjusted Close: Denotes the adjusted closing price of Google's stock, considering factors such as dividends and stock splits.
Adjusted High: Represents the adjusted highest value reached by Google's stock on the given day.
Adjusted Low: Represents the adjusted lowest value reached by Google's stock on the given day.
Adjusted Open: Indicates the adjusted opening value of Google's stock on the given day
Adjusted Volume: Represents the adjusted trading volume of Google's stock on the given day, accounting for factors such as stock splits.
Dividend Cash Amount: Denotes the amount of cash dividend paid out to shareholders on the given day.
Split Factor: Represents the split factor, if any, applied to Google's stock on the given day. A split factor of 1 indicates no split
You can find the dataset available on Kaggle at the following link: https://www.kaggle.com/datasets/shreenidhihipparagi/google-stock-prediction

WORKFLOW OVERVIEW:
This project involves the following steps:
Importing libraries and the dataset to be used for analysis.
Gathering insights from the dataset to understand its structure and contents.
Performing data pre-processing to prepare the data for model training.
Creating an LSTM (Long Short-Term Memory) model for stock price prediction.
Visualizing the actual stock prices vs. the predicted stock prices using the LSTM model.
Utilizing the trained model to predict stock prices for the upcoming 15 days.
