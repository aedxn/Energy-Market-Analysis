# Energy-Market-Analysis

This project is unfinished and still in progress. I use data from OECD and Eurostat to do some explorative data analysis on the current energy crisis. I then use daily gas spot prices from the US to do a time series analysis.

So far my work includes:

* Exploring and visualising monthly energy consumer price index for selected countries over time (Data: OECD)
* Visualisation of the gas price (Data: Eurostat)
* Visualisation of gas imports from russia of selected european countries (Data: Eurostat)

Using daily US gas prices my work includes:

* visualising the data
* Reducing seasonality of the date by using MA, seasonal decompositions and differencing
* plotting correlograms and applying statistical test to analyse seasonality and autocorrelation
* fitting and finding the best order of my ARIMA model
* using the ARIMA model to forecast gas prices
