# CO2 Emissions Forecasting

## Project Overview

This project, "Forecasting Annual CO2 Emissions in North America using Time Series Analysis," aims to model and forecast annual CO2 emissions using ARIMA models. The dataset consists of CO2 emissions data from 1949 to 2018.

## Dataset

The dataset contains annual CO2 emissions data for North America, measured in million metric tonnes of carbon dioxide, from 1949 to 2018. The data was sourced from various repositories, including the United Nations Framework Convention on Climate Change (UNFCCC) and the International Energy Agency (IEA).

## Methodology

1. **Data Pre-Processing**: Cleaning and preparing the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Analyzing the time series to understand trends, seasonality, and stationarity.
3. **Model Building**:
   - **ARIMA Models**: Identifying and fitting appropriate ARIMA models using Conditional Sum of Squares (CSS) and Maximum Likelihood (ML) methods.
   - **Model Evaluation**: Conducting residual analysis and diagnostic checks to ensure model adequacy.
4. **Forecasting**: Using the best-fit ARIMA model to forecast CO2 emissions for the next 10 years.

## Results

- **Best Model**: ARIMA(3,1,4) using Maximum Likelihood (ML) method.
- **Forecast**: The model forecasts CO2 emissions for the next decade, providing insights into future emission trends.

## Conclusion

The ARIMA(3,1,4) model was found to be the most suitable for forecasting annual CO2 emissions in North America. The model's residual analysis and diagnostic checks confirmed its adequacy, making it a reliable choice for future predictions.

## Files in the Repository

- `Time series project 1.Rmd`: RMarkdown script containing the code and analysis.


