# LSTM-sine-generator-keras
This little demo shows how to generate a sine with Keras LSTM. It feeds its own prediction back in, in order to generate a whole time series, and not just one point ahead in the future. 
It is still a little unstable, meaning the quality (especially the amplitude of the predicted sine) of output depends on the random seed. 
The output looks something like this:
![alt text](https://github.com/Binbose/LSTM-sine-generator-keras/blob/master/Sine%20generation%20LSTM.png)
