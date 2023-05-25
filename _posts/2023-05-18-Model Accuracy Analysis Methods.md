# Confusion matrix
A matrix that depicts the the ability of your model's image detection. Ideally values on the diagonal are one the rest are 0. It shows how many prediction are correct and incorrect per class. It helps in understanding the classes that are being confused by model as other class. The x axis is the actual data and y axis is the predicted data

![image](https://github.com/ENGGP/ENGGP.github.io/assets/90888168/3bdeb18b-dcdf-48d8-9a97-d38112a2de4a)


# Loss function
Loss is the penalty for a bad prediction. That is, loss is a number indicating how bad the model's prediction was on a single example. If the model's prediction is perfect, the loss is zero; otherwise, the loss is greater. The goal of training a model is to find a set of weights and biases that have low loss, on average, across all test images. There are 2 types of loss functions, regression and classification. Image below shows a regression loss function

![image](https://github.com/ENGGP/ENGGP.github.io/assets/90888168/9fc36e7e-a5dc-466b-9a76-743cc2d0095c)

# T-SNE
T-SNE algorithm can turn data in high dimentional space into 2 or 3 dimentional with scatter plot space hence making it easier to represent and visualise. It uses optimisational methods to minimise Kullback–Leibler divergence data in high dimention and in low dimentions so data in high dimention still retained and preserved in after it is converted to a lower dimention. Python librabry sklearner can be used to plot t-SNE. Perplexcity is is the most import hyperparametre as it can control the shape of the scatter plot.

![image](https://github.com/ENGGP/ENGGP.github.io/assets/90888168/bfdd3c63-a365-4452-a0b8-edcdfcf82060)

![image](https://github.com/ENGGP/ENGGP.github.io/assets/90888168/26309673-3980-4f18-90ad-de7638a5868c)

