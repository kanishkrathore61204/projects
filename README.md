# apmc-spatial-price-transmission
Python code that matches daily rainfall data to local agricultural markets based on geographic distance. It includes statistical tests to measure exactly how long weather events influence crop prices.
# Tracking How Weather Impacts Crop Prices in India

This project analyzes how daily weather events (like heavy rainfall) affect the wholesale prices of crops across India. 

A common challenge in agricultural research is correctly matching weather data to market locations. Often, researchers just look at the weather at the exact GPS coordinate of the market building. This project solves that problem by drawing geographic boundaries around each market to capture the actual rainfall happening on the surrounding farms and transport routes.

## Data Sources
* Market Prices:Daily wholesale crop prices from India's Agmarknet database. The code is built to handle massive datasets smoothly (over 75 million transaction records). Link- https://www.kaggle.com/datasets/khandelwalmanas/daily-commodity-prices-india/data
* Weather Data: Daily geographic rainfall grids from the India Meteorological Department (IMD).


