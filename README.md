# Files
```data.ipynb```: Data collection and basic formatting/filtering. Written to be run separately on multiple computers to mitigate rate-limiting.

```nn-1-lookback.ipynb```: First approach, simple neural network with limited preprocessing. High error.

```nn-2-lookback-classifier.ipynb```: Second approach, attempt to make a classification model work to reduce problem complexity. High error.

```nn-3-lookback-geomdelta.ipynb```: Third approach, using logarithms to turn ratios into differences, which may be easier for the network to work with. High error (though notably improved).

```nn-4-rnn.ipynb```: Final approach, using a recurrent neural network (LSTM layer) to improve time series understanding. Moderate error, most often accurate.

```model1.keras```: Best model produced by final approach. Loaded by livetest notebook.

```livetest.ipynb```: Loads model1, gets current stock price data, tests prediction against new data when it's available.