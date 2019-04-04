## Sentdex Rnn with Keras
### This is an ipynb notebook that attempts to speed up and simplify the creation of sequence data for the RNN that Harrison create in :
#### See (https://pythonprogramming.net/crypto-rnn-model-deep-learning-python-tensorflow-keras/)

This project contains 2 jupyter notebooks:
1. rnn_sentdex.ipynb: This is a reworked version of Harrison's original project at  (https://pythonprogramming.net/crypto-rnn-model-deep-learning-python-tensorflow-keras/), which attempts to simplify and speed up the creation of training and validation data for his RNN model.
2. rnn_sentdex_original.ipynb: This is a jupyter notebook that is almost identical to Harrison's code.  I have commented out the components of his tensorflow.keras.models.Sequential, and replaced them with keras.layers.SimpleRNN.  This replacement seems to run much faster, and arrive at the same place.

#### For more of Harrison's informative videos and posts, see his website (https://pythonprogramming.net/) or his youtube channel (https://www.youtube.com/channel/UCfzlCWGWYyIQ0aLC5w48gBQ)


