# Building-A-Two-Layer-Neural-Network-without-LibrariesOrDataframes

In SoftmaxRegression.py I implemented softmax regression for multi-class classification problems. By doing this project I got familiar with computing gradients of vectors/matrices. 
I used multi-class cross entropy as the loss function and stochastic gradient descent to train the model parameters.
Code correctness was tested by using nosetests and typing `nosetests test1.py` in the terminal.

**Neural Network**
In TwoLayerNeuralNetwork.py I implemented a classification method using fully-connected neural network (FC) with two layers.
The main goal was to extend softmax regression method in SoftmaxRegression.py to having multiple layers (instead of one layer in softmax regression).
In the first layer, the sigmoid activation function converts the linear logits into a non-linear activation.
In the second layer, we will use softmax as the activation function (the same as softmax regression in problem1). 
I used multi-class cross entropy as the loss function and stochastic gradient descent to train the model parameters.

Reused many functions seen in SoftmaxRegression.py
For example, sr.softmax() represents the softmax function you implemented in problem1.py.
Here 'sr' represents 'softmax regression'.
Tested code by typing `nosetests test2.py` in the terminal.

