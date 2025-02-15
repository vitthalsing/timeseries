# timeseries
The attached data shows monthly demand of  two different types of consumable items in a certain store from January 2002 to September 2017. The ultimate objective of this exercise is to predict sales for the period October 2017 to December 2018.

Read the data as time series objects in R. Plot the data. What are the major features you notice in the series? How do the two series differ?

Before a formal extraction of time series components is done, can you check for seasonal changes in the data for the two series separately? Particularly whether there are more variability in a season compared to the others, whether seasonal variations are changing across years etc. Compare the behavior of the two series.

Decompose each series to extract trend and seasonality, if there are any. Which seasonality is more appropriate – additive or multiplicative? Explain the seasonal indices. In which month(s) do you see higher sales and which month(s) you see lower sales? Any difference in the nature of demand of the two items?

Can you extract the residuals for the two decomposition exercises and check if they form a stationary series? Do a formal test for stationarity writing down the null and alternative hypothesis. What is your conclusion in each case?

Before the final forecast is undertaken one would like to compare a few models. Use the last 21 months as hold-out sample fit a suitable exponential smoothing model to the rest of the data and calculate MAPE. What are the values of α, β and γ? What role do they play in the modeling? For the same hold-out period compare forecast by decomposition and compute MAPE. Which model gives smaller MAPE? Give a comparison for the two demands.

Use the ‘best’ model obtained from above to forecast demand for the period Oct 2017 to December 2018 for both items. Provide forecasted values as well as their upper and lower confidence limits. If you are the store manager what decisions would you make after looking at the demand of the two items over years?
