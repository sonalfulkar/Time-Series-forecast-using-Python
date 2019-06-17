# time-series

Time series model
The purpose of below code is to understand time series model.

Characteristics of time series model:

It is time dependent. So the basic assumption of a linear regression model that the observations are independent doesn’t hold true in this case.
Along with an increasing or decreasing trend, most TS have some form of seasonality trends, i.e. variations specific to a particular time frame. For example, if you see the sales of a woolen jacket over time, you will invariably find higher sales in winter seasons.
Steps to follow:

Check if time series is stationary with Visual test, statistical test & Augmented Dickey Fuller Test
time series basic forecast:
Naive approach
Moving Average
Simple Exponential Smoothing
Holts Linear model
Holts Winter model
Make time series stationary -

it is critical if we want the forecasting model to work well.

Methods:

a. Differencing: we compute the difference of consecutive terms in the series. Differencing is typically performed to get rid of the varying mean

b. Seasonal Differencing: In seasonal differencing, instead of calculating the difference between consecutive values, we calculate the difference between an observation and a previous observation from the same season

c. Transformation: Transformations are used to stabilize the non-constant variance of a series. Common transformation methods include power transform, square root, and log transform; we will use log transform here

Forecase using ARIMA
