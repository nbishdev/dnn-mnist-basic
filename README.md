# Basic Fully Connected Neural Networks
Fully Connected Neural Networks for measuring and comparing the effects of using different activation functions as well as different number of intermediate dense layers to the classification process and output.

For all the experiments, we used the [MNIST database](https://en.wikipedia.org/wiki/MNIST_database).

We test the effect of the following set of parameters:
Activation Functions | Number of intermediate (dense) layers
:-: | :-:
`ReLU` | 5
`tanh` | 20
`Sigmoid` | 40

For every combination of these parameters we print the following metrics:
* Accuracy
* Precision
* Recall
* F1 score
