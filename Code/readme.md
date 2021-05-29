# Final Modeling Jupyter Notebooks

## Scenario 1

We try to predict future S&P 500 prices using past index prices.
We ran several models at the beginning of the project and included the following in our final code: FB Prophet, ARIMA, and a linear regression.

## Scenario 2

We try to improve FB Prophet. 
Specifically, we try to find coefficients for a linear model that minimizes the difference between actual S&P 500 prices and the FB Prophet predictions. 
Our features are macroeconomic data, and we later included some interaction terms between those linear features.

## General Notes

In both scenarios, we focus on using macroeconomic data (unemployment rate, federal funding rate, earning-per-share, etc.), rather than market data (price-to-earnings ratio, other stock prices, etc.).
