# Time-Series-Analysis
Time series models such as state space models, exponential smoothing models, arima, and more are used to predict future values within a series while taking into account previous values or values from other time series. Time series analysis is an interesting topic as the use cases have evolved with the innovations provided by some of the more recent advances in deep neural networks. Technically we can think of task such as generating images or deciding the next move in a video game as a time series problem. ie given the last "x" pixel values predict the next pixel. It is to be determined how this repo will evolve, but for the time being this repo will include simpler examples such as those involving financial time series.

# Projects
The projects included in this repo are utilizing different time-series analysis techniques. The projects are introductory explorations with commentary to explore different data preparatory and modeling techniques. 

## Project-1 (Stock Price Prediction)
This implementation is based on an example from a Udemy course on time series analysis from user "The Lazy Programmer" (https://www.udemy.com/share/104I9M3@d_79VEA3--YnE3luHxE5tsxlJX83-bYqfvDYc70TUy0ehTfuqMEdsVT2vnO0r_ti/). The purpose of this project is for stock price prediction using the auto arima model. 

## Project-2 (Volatility Prediction)
This implementation is a follow up to project 1 where instead of predicting the future mean price we are predicting the future volatility using the ARCH/GARCH models. This also includes an exploration in predicting the volatility of positive covid tests. 
