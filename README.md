# Comparative Analysis of Time Series Models for Stock Price Prediction

## Table of Contents
- [Project Description](#project-description)
- [Datasets](#datasets)
- [Methodology](#methodology)
  - [Time Series Models](#time-series-models)
  - [Evaluation Metrics](#evaluation-metrics)
  - [Data Partitioning](#data-partitioning)
- [Results and Discussion](#results-and-discussion)
  - [Facebook (Meta) Stock Price Prediction](#facebook-meta-stock-price-prediction)
  - [Walmart Stock Price Prediction](#walmart-stock-price-prediction)
  - [Impact of Data Partitioning](#impact-of-data-partitioning)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Contributors](#contributors)

## Project Description
This research study presents a comprehensive comparative analysis of various time series models for stock price prediction, focusing on two prominent companies: Facebook (Meta) and Walmart. The study evaluates the performance of multiple models, including Seasonal Exponential Smoothing (Holt-Winters), Gaussian Process Regression (GPR), Singular Spectrum Analysis (SSA), Neural Network Autoregression (NNAR), Temporal Convolutional Networks (TCN), ARIMA, Long Short-Term Memory (LSTM), Recurrent Neural Network (RNN), Gated Recurrent Unit (GRU), and Linear Regression (LR).

The primary goal of this project is to identify the most effective time series models for predicting stock prices for the selected companies and provide insights into the impact of different data partitioning strategies on model performance.

## Datasets
The study utilizes historical stock price data for Facebook (Meta) and Walmart, obtained from reliable sources such as Yahoo Finance or other reputable financial data providers. The dataset includes daily or weekly stock prices, covering a significant time period to ensure the robustness of the analysis.

## Methodology
### Time Series Models
The study evaluates the performance of the following time series models for stock price prediction:
- Seasonal Exponential Smoothing (Holt-Winters)
- Gaussian Process Regression (GPR)
- Singular Spectrum Analysis (SSA)
- Neural Network Autoregression (NNAR)
- Temporal Convolutional Networks (TCN)
- ARIMA
- Long Short-Term Memory (LSTM)
- Recurrent Neural Network (RNN)
- Gated Recurrent Unit (GRU)
- Linear Regression (LR)

### Evaluation Metrics
The performance of the models is assessed using the following evaluation metrics:
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- Mean Absolute Error (MAE)

### Data Partitioning
Two different train-test split ratios are employed to evaluate the models' predictive capabilities:
1. 70:30 (train:test) split
2. 80:20 (train:test) split

## Results and Discussion
### Facebook (Meta) Stock Price Prediction
The study presents the comparative analysis of the time series models for predicting Facebook (Meta) stock prices. The results highlight the strengths and weaknesses of each model, providing insights into their suitability for forecasting stock prices.

### Walmart Stock Price Prediction
The analysis is extended to Walmart's stock prices, and the performance of the time series models is evaluated and compared. The findings offer valuable insights into the models' performance in predicting stock prices for this second company.

### Impact of Data Partitioning
The study investigates the impact of different data partitioning strategies (70:30 and 80:20 train-test splits) on the models' predictive performance. The results demonstrate how the choice of data partitioning can influence the accuracy of stock price forecasts.

## Conclusion
The findings of this study provide a comprehensive understanding of the performance of various time series models in predicting stock prices for Facebook (Meta) and Walmart. The results offer valuable insights for investors, financial analysts, and traders, enabling them to make informed decisions when selecting appropriate models for stock price forecasting.

## Future Work
Building upon the findings of this study, future research can explore the following directions:
- Investigating the impact of additional factors (e.g., macroeconomic indicators, news sentiment) on stock price prediction
- Developing hybrid or ensemble models that combine the strengths of different time series techniques
- Exploring the applicability of the models to other companies or industries
- Incorporating more advanced data preprocessing and feature engineering techniques to enhance model performance

## Contributors
- Vo Quang Huy 
- Nguyen Hai Dang 
- Nguyen Nhat Minh 
- Nguyen Hai Dang 
- Lam Xuong Tin
