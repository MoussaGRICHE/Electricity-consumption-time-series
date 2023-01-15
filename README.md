# Electricity-consumption-time-series
##Objective:

Forecast electricity consumption (kW) for 2/18/2010 with and without using outdoor temperature information
Based on information from 1/1/2010 1:15 to 2/17/2010 23:45

##Data Files Information:

    3 columns: Timestamp, Power(kW), Temps (C°)
    4700 observations for Timestamp and Temps (Co): Information from 1/1/2010 1:15 to 2/18/2010 23:45
    4603 observations for Power(kW): Information from 1/1/2010 1:15 to 2/17/2010 23:45

## Time series information
This time series is a high frequency time series (observation each 15 minutes, so 96 observation per day) and with double seasonality (daily and weekly seasonality).

In this analysis, we analyse this time series with only daily seasonality and with double seasonality. The model with less overfitting will be chosen.

