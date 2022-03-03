# Mod11_challenge - Mercado Libre Time Series Analysis

# Overview
MercadoLibre is the most popular e-commerce site in Latin America. This analysis looks at the company's financial and user data
to help the company grow. It is trying to predict search traffic stock trading patterns. It looks at time series data,
seasonality and forecasts with Prophet.

# Technical Details

This analysis was completed in Google colab at (https://colab.research.google.com/drive/1GGnkd03EA_a61udOBzKNBlTUDINFq_DM#scrollTo=-ncJFW68L5VQ)

Requires Facebook Prophet

# Requires following libraries and imports
'''
!pip install pystan
!pip install fbprophet
!pip install hvplot
!pip install holoviews

# Import the required libraries and dependencies
import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
numpy as np

'''

# Looked for patterns in search trends across time
![Graph from May 2020 search trends](May_2020_Search_Trends)

# Looked at trends by the days of the week
![Graph from Search Trends on Days of Week](Mercado_trends_by_day_of_week)

# Looked at trends on a heatmap
![Trends by Heatmap](mercado_trends_heatmap)

# Looked at search trends by week of year
![Trends by Week of Year](mercado_trends_by_week_of_year)

# Looked at close price over years
![Close Price Over Years](close_price_over_years)

# Looked at close and search trends for the first half of 2020
![First Half 2020](close_and_search_first_half_2020)

# Looked at Stock Volatility
![Stock Volatility](stock_volatility)

# Looked at forecast trends
![Forecast Trends](trends_plot)

# Looked at Predictions
![Predictions](yhat_plots)

# Looked at some component time series plots
![Components](components_1)
![Components](components_2)

# Creator
Ann Howell with support from Rice University FinTech Bootcamp

# License
MIT