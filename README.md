# Image_classification_using_pytorch



The Aim of this project was to classify images present in FahionMNIST with their probabilities.


Number of epoches was set to 5. With increase in number of epoches we can see much lower training and test loss but we have compramise with computation time.


The neural Network has 2 hidden layers and 10 output values(10 features). For both hidden Layers we followed Relu activation function and for output layer we used log softmax function.

We have set backpropagation through Adam optimizer and to ovoid overfit we have set dropout function.
