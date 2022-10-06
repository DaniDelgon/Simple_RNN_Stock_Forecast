# Simple_RNN_Stock_Forecast
In this project, our knowledge about RNNs will be applied to train models that are capable of predicting the behaviour of the time series. To do so, a stock price dataset will be used to predict the future values of the time series through the application of RNN. We will see how modelling using RNN is a very good option in these cases of time series.

![índice2](https://user-images.githubusercontent.com/18196870/194307998-2b38bfa7-b3b3-4ec4-9939-abc1c7a5b884.png)

As you can see, we train our model in the training set, which holds a period from 2009 to 2020, and the test set that we use comprehends the last two years, but we display the test performance only during year 2020, because the further we get from the initial point, the prediction error is bigger, as when you get a meteorological prediction, the further in time is the prediction, the error normally gets bigger, and the probebility of the meteorological prediction gets more uncertain to occur.

![índice](https://user-images.githubusercontent.com/18196870/194301221-a941fae3-c298-4877-af53-b4f5436c0a89.png)

We can see that as a result of this miniproject, our model have learning some patterns of this stock and have some acceptable just by training it with the closes prices of the stock we are studying. But we can further improve this forecasting with some finance feature engineering, by training this model with candle data, MACD... instead of solely training it with the close price, but as a proof of concept, the results just with the Close prices are acceptable.
