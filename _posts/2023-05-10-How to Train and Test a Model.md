# How to Train and Test a Model

By simply using FastAi, an model for image detection can be produced. In this example we will be training a model that recognises birds and forests. This is done through the following steps
- Download 200-300 images of birds and forests.
- Move 20-50 images from your image pool into a new folder for testing
- Load the image pool into data loader function
- Call function vision_learner on the data loader and tune it over 3 iterations
- Tuning stage usual takes a whil
- Run confusion matrix, loss function and t-SNE on the test folder to test the model's performance

## What is data loader
After the images were downloaded, the data loader function was then called on 'animal' folder. Data loader transforms images into a format that is readable by FastAi. Following dot points explains DataBlock function's parameters.
- blocks - Indicated the input and output image type. ImageBlock is the input type and CategoryBlock is the output type.
- get_items - returns the image files
- splitter - splits the image pool into two sectionsm validation and training.
- get_y - return the name of the parent folder
- The images were squishes the images to scale to the same size

## How RandomSplitter work
RandomSplitter will divide up all the images in the pool into training set and validation set. Training set will train the model 
to regconise certain images. Validation set is a set of images that will be used to test your model.

