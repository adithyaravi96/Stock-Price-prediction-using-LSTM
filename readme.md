
### Stock Price Prediction using LSTM

This repository contains a Python script that utilizes a Long Short-Term Memory (LSTM) model for predicting the stock price of Reliance Industries Limited (RELIANCE.NS). The script demonstrates how to preprocess the data, build an LSTM model, and evaluate its performance. Below are the details of the code and its functionality:


## Libraries Used

os: Operating system library for file operations.
pandas: Data manipulation library.
numpy: Numerical operations library.
math: Mathematical functions and constants.
datetime: Handling date and time data.
matplotlib: Data visualization library.
scikit-learn: Machine learning library for evaluation metrics and data preprocessing.
tensorflow: Deep learning library.
yfinance: Library for downloading historical stock data.
## Getting Started
Import the necessary libraries.
Download historical stock data for Reliance Industries Limited (RELIANCE.NS) using yfinance.
Data exploration and preprocessing.
Train-test split and data normalization using MinMaxScaler.
## Model Building
Build a sequential LSTM model with one hidden layer and one output layer.
## Training and Evaluation
Train the model using historical stock data.
Evaluate the model using evaluation metrics such as RMSE, MSE, MAE, explained variance score, R2 score, mean gamma deviance, and mean poisson deviance.
## Model Saving
Save the trained model to a file.
## Predicting Future Stock Prices
Predict future stock prices for a specified number of days using the trained model.
## Visualization
Plot the original close price vs. predicted close price for a given time period.
Plot the last 15 days' close price vs. predicted next 30 days' close price.
Plot the entire closing stock price history along with predictions.

## How to Use
Clone this repository to your local machine.
Make sure you have all the required libraries installed (mentioned in the script).
Run the script and follow the comments for each step.
Feel free to modify and experiment with the code to explore different aspects of stock price prediction using LSTM models.
## Screenshots 

# stock Data Visualisation:
![stock data](https://github.com/adithyaravi96/Stock-Price-prediction-using-LSTM/assets/131150097/e2c9b4a9-f540-4a54-86a8-9aaae2b6e887)

# Charting with MA200:
![ma200](https://github.com/adithyaravi96/Stock-Price-prediction-using-LSTM/assets/131150097/2bc3b0e8-441d-4e8f-8dba-b36f936be120)

# Period considered :
![considered period](https://github.com/adithyaravi96/Stock-Price-prediction-using-LSTM/assets/131150097/9f85e706-6aab-4673-bfb4-999f38bb6dbb)

# Predited model comparison Test/Train :
![train data and test data](https://github.com/adithyaravi96/Stock-Price-prediction-using-LSTM/assets/131150097/c93c187a-365d-4121-a59f-ad2413998587)

# loss evaluation :
![outputalidation loss](https://github.com/adithyaravi96/Stock-Price-prediction-using-LSTM/assets/131150097/0ba31752-1ae5-4361-8cb2-fc2ce8aa8b8d)

# comparing last 15 days to predicted next 30 days :
![comparing](https://github.com/adithyaravi96/Stock-Price-prediction-using-LSTM/assets/131150097/37eb96a3-0059-4771-a2e6-30908f1a4ec7)

# Final appending the prediction to the considered period :
![predicted](https://github.com/adithyaravi96/Stock-Price-prediction-using-LSTM/assets/131150097/b1e42fe3-c8dc-4289-9634-52dbc26332d1)



For recruiters and data science professionals looking for expertise in data analysis and stock price prediction, please don't hesitate to reach out. I'm open to collaborations and new opportunities in the field of data science and analytics. Let's connect!

#DataScience #DataAnalytics #MachineLearning #LSTM #StockPrediction #RelianceIndustries #TensorFlow #Keras #Pandas #Numpy #Matplotlib #GitHub #DataScienceJobs #DataAnalyticsJobs #CareerOpportunities #LinkedIn #ConnectWithMe

Connect with me on LinkedIn: www.linkedin.com/in/adhithyanravi
