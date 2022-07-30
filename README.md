# Project-1-Predicting-Bike-Sharing-Patterns-NN
**Predicting Bike Sharing is Neural Network project  in the deep learning Nanodegree**

This project builds Neural Network from Bike sharing Dataset from https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset
to predict the number of bikes needed per day 

##unit-test cases in the Project##

1-The activation function should be a sigmoid
2-The number of epochs should be between 50 and 15000
3-The number of hidden nodes should be 5 and 100
4-There should be exactly one output node
5-The learning_rate should be between 0.05 and 5
6-As already mentioned in the test-cases in Your_first_neural_network.ipynb, for the given NeuralNetwork(3, 2, 1, 0.5), the forward pass implementation, backpropagation implementation, and update_weights implementation should be correct. Expected updated weights are:
Hidden to output = [[0.37275328], [-0.03172939]]
Input to hidden=[[0.10562014, -0.20185996], [0.39775194, 0.50074398], [-0.29887597, 0.19962801]]
7-The run method should have an expected input as 0.09998924
8-Produces good results when running the network on full data. Requirements are:
9-Training loss should be less than 0.09
10-Validation loss should be less than 0.18


As we can see, the Training loss = 0.07and the Validation loss=0.15 which is great but you can observe that the model overestimates bike ridership in December because it hasn't had sufficient holiday season training examples. The predictions generally are quite accurate, though!
