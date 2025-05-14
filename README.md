# Impact of Sentiment Analysis on Financial Price Prediction: Comparison between LSTM, BERT and FinBERT.

In the current economic context, increasing numbers of people are becoming interested in the world of investments, boosted by easier access to digital platforms and the growing globalization of markets. It is no longer just financial institutions or large funds, but also small investors seeking to make their capital profitable in the current economic uncertainty, inflation and low interest rates. This increased interest in the financial field has strengthened the need for tools that allow more informed, faster and efficient decision making.

Accordingly, the main objective of this project is to analyze the impact of sentiment analysis on financial price prediction by integrating textual information from economic news with historical market data. For this purpose, three different perspectives are compared: 
1.	**LSTM with historical data:** only the historical price time series is used as model input.
2.	**LSTM + BERT:** historical data is combined with sentiment vectors obtained from financial news analysis with the BERT language model.
3.	**LSTM + FinBERT:** similar to the previous approach but the sentiment analysis is performed with the FinBERT language model, specifically trained in the financial field.

The data acquisition necessary for this analysis will be done by calling different APIs: Yahoo Finance for historical prices and Finnhub for financial news. The texts will be processed through sentiment analysis techniques using the BERT and FinBERT language models. The results of this sentiment analysis will be used as input variables, together with historical price data to train an LSTM model. Finally, quantitative metrics will be used to evaluate the accuracy of each approach and determine which approach provides better results in forecasting market movements.
