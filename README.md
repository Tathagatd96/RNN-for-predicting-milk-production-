# RNN-for-predicting-milk-production-

## Getting Started
This implementation deals with the task of predicting the milk production capacity over a period of time based on previous production rates.

## Requirements
 * Python 3.5 or above + pip
 * Tensorflow 1.6 or above
 * Pandas
 * Numpy
 * Scikit-learn
 
 ## Training the model
 Run this file. It will take about 20 seconds depending on your processor. 
 ```python
 python train.py
 ```
 ## Running Test
 ```python
 python test.py
 ```
 ## Results
 
 ![milk_results](https://user-images.githubusercontent.com/28685502/42217348-71f8836c-7ee2-11e8-8d66-62d764e16d2b.png)
I trained the model for 6000 iterations, hence it overfits after reaching the peak value in the graph. Play around with the number of neurons and iterations to get better results.
