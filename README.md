# Stock-Price-Prediction

LSTMs are very powerful in sequence prediction problems because they’re able to store past information. This is important in our case because the previous price of a stock is crucial in predicting its future price.

Data is collected from the Bombay Stock Exchange(BSE) official site.

Data consists of the top 100 performing stock indexes from 3 April 2017 to 29 February 2020.

I have used the data for previous 3 years of the stock indexes as the training data and the testing data consists of stock indexes from 1 March 2020 till 4 May 2020.

Timestep of 60 has been used while predicting the stock indexes which means that it has been assumed that the performance of a stock on a particular day depends on the performance of the stock over the previous 60 days.

Data normalisation and preprocessing has been performed acordingly for feeding the data to the LSTM neural network.
