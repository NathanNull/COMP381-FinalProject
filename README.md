# Files
```nn-1-lookback```: First approach, simple neural network with limited preprocessing. High error.

```nn-2-lookback-classifier```: Second approach, attempt to make a classification model work to reduce problem complexity. High error.

```nn-3-lookback-geomdelta```: Third approach, using logarithms to turn ratios into differences, which may be easier for the network to work with. High error (though notably improved).

```nn-4-rnn```: Final approach, using a recurrent neural network (LSTM) to improve time series understanding. Moderate error, is often very accurate.

```model1.keras```: Best model produced by final approach. 