# Fintech Bootcamp Module 11 Challenge - Forecasting using Prophet

Assignment is done in Google Colab: https://colab.research.google.com/drive/1WG8WE94UxoB0L_kAo0i1DVPKbFuoIWW0?usp=sharing

## The summary of the findings:
###  Find Unusual Patterns in Hourly Google Search Traffic
Q: Did the Google search traffic increase during the month that MercadoLibre released its financial results?
A: Yes, it is increased by more than 3000 from the median trend

### Mine the Search Traffic Data for Seasonality
Q: Does any day-of-week effect that you observe concentrate in just a few hours of that day?
A: Yes - we can see that for all days towards the end of the day and the begginig of the day is when most of the traffic happens

### Group the search data by the week of the year. Does the search traffic tend to increase during the winter holiday period
Q: Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?
A: We can see some weak negative correlation between the Lagged search trends and the stock volatility (-0.149). There is no correlation with the hourly stock return

### Create a Time Series Model with Prophet
Q: What time of day exhibits the greatest popularity?
A: This is during midnight

Q: Which day of week gets the most search traffic?
A: Tuesday is the most popular day

Q: What's the lowest point for search traffic in the calendar year?
A: October is the lowest point

### Forecast Revenue by Using Time Series Models
Q: Based on the forecast information generated above, produce a sales forecast for the finance division, giving them a number for expected total sales next quarter. Include best and worst case scenarios, to better help the finance team plan.
A: The most likely sales forecast in the next quarter is 1.945B dollars. The worst case scenario is 1.773B dollars and the best case scenario is 2.117 bilion dollars in sales
