# NVIDIA_Shares

<p align="center">
  <img src="https://web-cdn.markets.com/nvidia_stock_width_1200_format_jpeg_2de49a2c8e.jpg.webp">
</p>

## Description
This project aims to predict the number of Nvidia shares traded over time using different time series predictive methods. In the context of finance, a company's stock market predictions can provide valuable information for investors, analysts, and market participants. Nvidia, one of the most prominent companies in the semiconductor and technology industries, has been particularly notable for its innovations in artificial intelligence and video games, making its stock market predictions of great interest.

## Objectives:
The primary objective of this project is to develop a predictive model to forecast the future behavior of Nvidia's stock volume. Using a variety of time series analysis methods, we will seek to identify past patterns and trends that can help predict future stock trading volumes. Stock volume predictions are crucial for understanding market liquidity, stock price volatility, and trading trends.

## Methodology:
This project employs both simple and complex methods to predict Nvidia stock volumes. The methods used fall into two main categories:

### Simple Methods:
- `Simple Smoothing (Simple Moving Average-SMA)`: Calculates the average of a set of observations over a given time interval. It is useful when the data show little variability and do not exhibit complex trends or seasonality.

- `Double Exponential Smoothing`: This method considers both the level and the trend of the data. It is useful when the data shows a linear trend, either increasing or decreasing. The forecast adjusts based on recent observations and changes in the trend.

- `Holt-Winters`: Extends smoothing techniques by adding trend and seasonality components. It is suited for data with both trends and regular seasonal patterns. The model separates the time series into level, trend, and seasonality components.



### Complex Methods:
- `ARIMA (AutoRegressive Integrated Moving Average)`: The ARIMA model is widely used for time series prediction, particularly with stationary or differenced data. It combines autoregression, moving average, and differencing to capture linear patterns. In this project, ARIMA models trends and temporal dependencies in Nvidia stock volumes.
- `AutoARIMA`: AutoARIMA extends ARIMA by automating model and parameter selection. It optimizes the model without manual intervention, improving efficiency and accuracy. Selection is based on criteria like AIC and BIC to find the best fit for the data.

## Model Evaluation:

Throughout the project, the models will be evaluated using standard prediction error metrics, such as **RMSE** (Root Mean Square Error), which measures the magnitude of the error between predictions and actual values, penalizing large errors due to the square of the differences; **MAE** (Mean Absolute Error), which calculates the average of the absolute errors between predictions and actual values, making it more robust to outliers; and **MSE** (Mean Squared Error), which measures the average of the squared errors and penalizes large errors more heavily, making it a useful metric when minimizing error variance.

These metrics will allow the accuracy of the predictions made by the different models used in this project to be compared and evaluated.


## Data Source:
The data used comes from a database available on Kaggle, specifically for Nvidia stock predictions. This data contains historical information on Nvidia stock, including opening and closing prices, highs, lows, trading volumes, and other parameters relevant to stock analysis over a given period.

The data source is available at: [Nvidia Stock Prediction](https://www.kaggle.com/code/joshuabaliliongcoy/nvidia-stock-prediction-with-time-series-analysis/input) 


