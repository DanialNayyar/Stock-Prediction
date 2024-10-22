# Stock-Prediction
First attempt - Task was to predict if tomorrows price is higher/lower than todays
Used the s&p 500 from yahoo finance, with the data going from januar 1980 to january 2024

Used the precision score metric from sklearn and grid search to get the best parameters for random forrest classifier
Initial score was low, around 0.5, so instead of testing it, I decided to add in indicator data as well. Indicators chosen were the RSI and MACD (relatively commmonly used indicators by traders).

Used the classfier again, updating it with the new data as well as reconsiering the hyperparemeters used earlier on.

Final Precision Score: 0.9


# Next Steps...
Learn and Implement time series forecasting and reinforcement learning to predict exact closing price
