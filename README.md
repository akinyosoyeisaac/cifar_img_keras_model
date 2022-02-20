# cifar_img_keras_model

# BUILDING A SEQUENTIAL KERAS MODEL TO TRAIN AND PREDICT IMAGES OF OBJECT FROM THE CIFAR DATASET

- [x] Data Source
* [from kaggle](https://www.kaggle.com/c/cifar-10/data)

This is a simple model building using stack of dense layers in the keras library.

## PERFORMANCE
- Obviously looking at the peformance of the model it might not be too difficult to suspect that the model is overfitting as their is a great divergent between the train accuracy and the validation accuracy same can be said of train loss and validation loss
- To resolve this I will propose the following approach which I will be looking into in the future time but as at the time of writing I don't have the computation resource to do so.
	1. Since the shape is 3-dimension that is the [channel, height, wight] to improve the performace of the model one can make use of convolution layer
	2. Also to reduce overfitting one approach to make use of is to make use of the early stopping callback
	3. Hyperparameter tunning of the model such as the inital weight, optimizer, learning rate, loss, epochs, steps, number of neurons, number of layers, activation function etc
	4. Also one can leverage on the other layers like normalization (l1 or l2 or both), batch normalization, dropout etc
	5. For further reference on how to improve your model I will also suggest you read page 325-363 of **Hands-on machine learning with scikit-learn and tensorflow 2e**
> It is importance I point out that is my first attempt using keras to model and make prediction so I apologies of any inconsistence and everything in the notebook above is purely my hand work.
> I will also be glad to welcome your comments and suggestions with open heart 

> # THANKS FOR YOUR TIME 