# LSTM model description 
This is a modified version of LSTM made for trend analysis. We know that prediction stock market price is impossible because of Random walk and Brownian motion law in finanical market. But we can predict the trend of the stock market.

## Hyperparametes which yielded best output
We found that the for output which yielded best depended on 60 timestamps before and the number of layers are 4 with 50 neurons each. Dropout regurlarization with keep probability of 0.2 was used to avoid overfitting. The activation function used is tanh and the dense output layer is linear activation fucntion.

### The Programming Language used is **Keras**
