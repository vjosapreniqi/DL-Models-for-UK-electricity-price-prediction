# Deep-Learning-for-UK-electricity-prices
As additional part of the UK electricity price prediction with machine learning,we have developed an another experiment by utilizing Deep learning algorithms. 
Respectively, Recurrent Neural Networks (RNN), Long – Short Term Memory (LSTM) and Convolution Neural Networks (CNN) in order to predict the UK electricity prices. In general, both RNN and LSTM fall into recurrent neural networks; however, LSTM works better for deeper networks and it is more compatible with time series. On the other hand, CNN models are very well known in the computer vision field, image recognition, and object detection. However, when combining LSTM with CNN layer on top of the model, we have yelded the best results for prediction univariate time series (time + electricity prices). Whereas, for multivariate time series (time + electricity prices, gas prices, and Initial load demand) the model with only one LSTM layer gives the best results. 
In this repo, there are two python/jupiter files that contain the models for univariate time-series and multivariate time-series, and one csv. file which handles the data. 


