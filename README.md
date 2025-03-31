EC455 Final Project

Authors

Carson Boettinger and Nithin Kumar

Overview

This project analyzes historical commodity price data using time series techniques. The analysis includes data preprocessing, visualization, transformations, and autocorrelation analysis to understand the trends and stationarity of different commodities over time.

Project Structure

Data Import & Preprocessing: Reads historical price data for multiple commodities and filters it to the date range 1980-2019.

Data Visualization: Uses ggplot2 to generate time series plots for different commodities.

Time Series Transformations: Applies log transformations and differencing to analyze stationarity.

Autocorrelation Analysis: Computes and visualizes ACF and PACF plots to identify dependencies in the data.

Dependencies

Ensure you have the following R libraries installed before running the scripts:

install.packages(c("tidyverse", "tseries", "urca", "vars", "lmtest", "forecast", "xts", "ggplot2", "corrplot", "gridExtra", "lubridate", "dplyr", "tidyr"))

How to Run

Open EC455_Final_Project.Rmd in RStudio.

Run all code chunks to process the data, generate visualizations, and perform time series analysis.

Data

The dataset includes historical prices for the following commodities:

Coffee

Copper

Corn

Cotton

Lumber

Oats

Soybean

Wheat

Data files should be placed in the CommodityEC455/ directory before running the analysis.

Key Outputs

Time series plots for each commodity

Transformed series (log, first difference, log first difference)

ACF and PACF plots for log-differenced series

Summary statistics for each transformation

Future Improvements

Extend analysis with ARIMA modeling for forecasting

Implement cointegration tests to analyze long-term relationships

Automate data updates from external sources

License

This project is for academic purposes. Feel free to use and modify with attribution.

For any questions or contributions, please reach out to the authors.

