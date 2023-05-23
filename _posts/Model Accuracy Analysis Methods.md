# Confusion matrix
A matrix that depicts the the ability of your model's image detection. Ideally values on the diagonal are one the rest are 0.
It shows how many prediction are correct and incorrect per class. It helps in understanding the classes that are being confused
by model as other class.

# Loss function
Loss is the penalty for a bad prediction. That is, loss is a number indicating how bad the model's prediction was on a single example. If the model's prediction is perfect, the loss is zero; otherwise, the loss is greater. The goal of training a model is to find a set of weights and biases that have low loss, on average, across all test images.

# How RandomSplitter work
RandomSplitter will divide up all the images in the pool into training set and validation set. Training set will train the model 
to regconise certain images. Validation set is a set of images that will be used to test your model.
