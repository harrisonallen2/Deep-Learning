LSTM Stock Predictor

![deep-learning.jpg](Aspose.Words.4254ab45-5ca3-472e-b97c-16aa614f6499.001.jpeg)

Background

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

In this assignment, you will use deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

You will need to:

1. Prepare the data for training and testing
1. Build and train custom LSTM RNNs
1. Evaluate the performance of each model

Finally, use the testing data to evaluate each model and compare the performance. Use the above to answer the following:

- Which model has a lower loss?
- Answer:The model with the lower loss is the closing prices predictor

![lower\_loss\_CP.png](Aspose.Words.4254ab45-5ca3-472e-b97c-16aa614f6499.002.png)

- Which model tracks the actual values better over time?
- Answer:The model with better results over time is the closing prices predictor

![actual\_vc\_predictedCP.png](Aspose.Words.4254ab45-5ca3-472e-b97c-16aa614f6499.003.png)

- Which window size works best for the model?
- Answer:The window size that works better is 1

