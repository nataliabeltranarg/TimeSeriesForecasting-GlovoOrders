# Time Series Forecasting: Glovo Order Prediction in Barcelona,Spain 

This project aimed to predict the number of orders Glovo will receive on an hourly basis for the upcoming week. The predictions will help optimize the number of couriers required, ensuring efficient service without excess idle time or delayed deliveries. 

## Project Overview 

Glovo currently relies on manual decision-making to determine the number of couriers needed for each hourly slot in every city. With the growing number of cities and orders, this approach is becoming unsustainable. The goal of this project is to automate the process by predicting the number of orders for each hour of the upcoming week. This will enable Glovo to better allocate couriers and improve operational efficiency. 

## Data Source 

The dataset used for this project is 'data_BCN.csv', which contains historical data on the number of orders in Barcelona. The data is structured with hourly time slots, and covers multiple weeks, providing a rich data set for analysis. 

## Exploratory Data Analysis (EDA)

The EDA section involves exploring the data to understand trends, cycles, and seasonal patterns, as well as outliers or anomalies that might affect the model's performance. 

**Key Findings** 
- **Trends**: Identifying any long-term increase or decrease in the number of orders 
- **Seasonality**: Determining if there are weekly, daily, or hourly patterns in order volume 
- **Outliers**: Detect any unusual spikes or drops in orders that deviate from established patterns.

## Modeling 

We experimented with several models to predict the hourly order count for the upcoming weeks: 
- ARIMA (AutoRegressive Integrated Moving Average)
- SARIMA (Seasonal Autoregressive Integrated Moving Average)
- LASSO
- Linear Regression
- XGBoost

## Contributors 
- Natalia Beltran
- Clarice Mottet
- Tatiana Bakwenye
