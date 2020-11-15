# Stock-Price-Prediction

Stock price predition using Long Short Term Memory (LSTM)

## Aim

In Stock Market Prediction, the aim is to predict the future value of the financial stocks of a company. The recent trend in stock market prediction technologies is the use of machine learning which makes predictions based on the values of current stock market indices by training on their previous values.

## Background

Nowadays, the most significant challenges in the stock market is to predict the stock prices. The stock price data represents a financial time series data which becomes more difficult to predict due to its characteristics and dynamic nature. Earlier algorithms like support vector machines, regression and backpropagation were used which gave accuracy to certain level. Here I have implemented LSTM model to predict the stock prices.

## Algorithm

### LSTM

An LSTM has a similar control flow as a recurrent neural network. It processes data passing on information as it propagates forward. The differences are the operations within the LSTM’s cells. The concept of LSTM’s are the cell state, and it’s various gates. The cell state act as a transport highway that transfers relative information all the way down the sequence chain. You can think of it as the “memory” of the network. The cell state, in theory, can carry relevant information throughout the processing of the sequence. So even information from the earlier time steps can make it’s way to later time steps, reducing the effects of short-term memory. As the cell state goes on its journey, information get’s added or removed to the cell state via gates. The gates are different neural networks that decide which information is allowed on the cell state. The gates can learn what information is relevant to keep or forget during training.

## Methodology

1. Importing packages
2. Reading and analyzing data using pandas
3. Normalizing the data using sklearn
4. Converting data to supervised learning problem
5. Creating model using keras
6. Training the model
7. Predicting and visualizing the result


## Libraries Used

This project uses following libraries

..* NumPy (https://numpy.org/)
..* Pandas (https://pandas.pydata.org/)
..* Matplotlib (https://matplotlib.org/)
..* Keras (https://keras.io/)
..* sklearn (https://scikit-learn.org/)
..* Tenserflow (https://www.tensorflow.org/)






