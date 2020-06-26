# Deep-Learning-for-UK-electricity-prices

As an additional investigation on the UK electricity price prediction with machine learning, we have developed another experiment by utilizing Deep learning algorithms. 
The algorithms used to predict the UK electricity prices for this task are Recurrent Neural Networks (RNN), Long – Short Term Memory (LSTM) and Convolution Neural Networks (CNN). In general, both RNN and LSTM fall into recurrent neural networks; however, LSTM works better for deeper networks and it is more compatible with time series. On the other hand, CNN models are very well known in the computer vision field, image recognition, and object detection. However, when combining LSTM with a CNN layer on top of the model, we have yielded the best results for predicting the univariate time series (time + electricity prices). Whereas, for multivariate time series (time + electricity prices, gas prices, and Initial load demand) the model with only one LSTM layer gives the best results. 

## Technical info
Under the directory named Data, the csv files which contain the half-hourly electricity prices can be found.
Models folder contains the pre-trained models, whereas Notebooks folder contains two Jupyter notebooks, one for univariate time series prediction models and the other for multivariate time-series predictions.

## Prerequisites
- Clone the repository: `git clone https://github.com/vjosapreniqi/Deep-Learning-for-UK-electricity-price-prediction.git`
- Install the requirements `pip install -r ./requirements.txt`

