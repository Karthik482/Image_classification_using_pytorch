# Image_classification_using_pytorch


This project aimed to classify images present in FahionMNIST with their probabilities.


The number of epochs was set to 10. With an increase in the number of epochs we can see much lower training and test loss and higher accuracy but we have compromise with computation time.


The neural network has 2 hidden layers and 10 output values(10 features). For both hidden Layers we followed the Relu activation function and for the output layer we used log softmax function.

We have set backpropagation through Adam optimizer and to ovoid overfit we have set dropout function.

![image](https://user-images.githubusercontent.com/55606550/82617065-eb1d7080-9b9c-11ea-8ccc-a74c6cc51d81.png)
![image](https://user-images.githubusercontent.com/55606550/82617208-5cf5ba00-9b9d-11ea-8231-b791ebb221c4.png)
