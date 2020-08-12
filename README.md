# HSI_LSTM_Baseline

Enviroment: macOS Catalina 10.15.4, python 3.7, sklearn, Tensorflow 2.0

Data: Hang Seng Index Futures from 2010.  From Investing.com

Only use the 'Close' price to Time Series Predict, use the RNN LSTM, the result is not good.

Can not good to predict the turning point, so if predict 10 days price, if one day mistake the turning point, the prediction is far from real price.

Still looking for the solution...
