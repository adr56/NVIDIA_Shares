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
- `Simple Smoothing (Simple Moving Average-SMA)`: Simple smoothing calculates the average of a set of observations over a given time interval. It is useful when the data show little variability and do not exhibit complex trends or seasonality.

- `Double Exponential Smoothing`: This method consider both, the level and the trend of the data. It is particularly useful when the data exhibits a linear trend, either increasing or decreasing, over time. The approach adjusts the forecast not only based on the recent observations but also accounts for the trend, making it more responsive to changes in the direction of the data.

- `Holt-Winters`: The Holt-Winters method is an extension of smoothing methods, which includes trend and seasonality components. This approach is suitable for data that exhibit both an increasing or decreasing trend and regular seasonal patterns. The model is divided into three key components: level, trend, and seasonality. It is very effective for predicting time series with strong seasonality and can be used for data with both additive and multiplicative seasonality.

### Complex Methods:
- `ARIMA (AutoRegressive Integrated Moving Average)`: The ARIMA model is one of the most widely used models for time series prediction, especially when the data are stationary or can be transformed into stationary data through differencing. ARIMA combines three key components: autoregression (AR), moving average (MA), and differencing (D), making it a powerful approach for capturing linear patterns in data. In this project, ARIMA is used to model trends and temporal dependencies in Nvidia stock volumes, especially when the data exhibits complex long-term behavior.

- `AutoARIMA`: AutoARIMA is an automatic extension of the ARIMA model that uses automated model and parameter selection methods. This facilitates model optimization without manual intervention, which can save time and improve model accuracy. AutoARIMA automatically selects the best ARIMA model for the available data, based on criteria such as the Akaike Information Criterion (AIC) or the Bayesian Information Criterion (BIC).


## Model Evaluation:
Predictive Performance: Throughout the project, models will be evaluated using standard prediction error metrics such as RMSE (Root Mean Square Error) and MAE (Mean Absolute Error).


## Evaluación del Modelo

Throughout the project, the models will be evaluated using standard prediction error metrics, such as **RMSE** (Root Mean Square Error), which measures the magnitude of the error between predictions and actual values, penalizing large errors due to the square of the differences; **MAE** (Mean Absolute Error), which calculates the average of the absolute errors between predictions and actual values, making it more robust to outliers; and **MSE** (Mean Squared Error), which measures the average of the squared errors and penalizes large errors more heavily, making it a useful metric when minimizing error variance.

These metrics will allow the accuracy of the predictions made by the different models used in this project to be compared and evaluated.


## Data Source:
The data used comes from a database available on Kaggle, specifically for Nvidia stock predictions. This data contains historical information on Nvidia stock, including opening and closing prices, highs, lows, trading volumes, and other parameters relevant to stock analysis over a given period.

The data source is available at: [Nvidia Stock Prediction](https://www.kaggle.com/code/joshuabaliliongcoy/nvidia-stock-prediction-with-time-series-analysis/input) 


