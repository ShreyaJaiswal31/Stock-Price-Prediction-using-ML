# Stock-Price-Prediction-using-ML
This project utilizes machine learning techniques to predict stock prices based on historical market data. By leveraging various regression models, time series forecasting methods, and deep learning approaches, the project aims to analyze stock trends and provide future price predictions.

Machine learning has significant applications in the stock price prediction. In this machine learning project, we will be talking about predicting the returns on stocks. This is a very complex task and has uncertainties. We will develop this project into two parts:
First, we will learn how to predict stock price using the LSTM neural network.
Then we will build a dashboard using Plotly dash for stock analysis.

**Stock Price Prediction Project**

**Datasets**

1. To build the stock price prediction model, we will use the **NSE TATA GLOBAL** dataset. This is a dataset of Tata Beverages from Tata Global Beverages Limited, National Stock Exchange of India.
   
3. To develop the dashboard for stock analysis we will use another stock dataset with multiple stocks like Apple, Microsoft, Facebook.

**Stock price prediction using LSTM**
1. Imports libraries
2. Read the dataset
3. Analyze the closing prices from dataframe
4. Sort the dataset on date time and filter “Date” and “Close” columns
5. Normalize the new filtered dataset
6. Build and train the LSTM model
7. Take a sample of a dataset to make stock price predictions using the LSTM model
8. Save the LSTM model
9. Visualize the predicted stock costs with actual stock costs
    
Here, you can observe that LSTM has predicted stocks similar to actual stocks.

**Build the dashboard using Plotly dash**
1. Imports libaries
2. Reas the dataset
3. Load the LSTM Model
4. Run the Dash Application

Here, You can see an interactive dashboard for stock analysis.
