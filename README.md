# Deep Image Classifier using Convolution Neural Network.

Here we build a deep image classifier to classify happy and sad images using tensorflow and keras library.

## Steps involved in the process


### 1.Building a data pipeline 
Installed some dependencies like tensorflow, opencv and matplotlib.

Downloaded some happy and sad images from google for this project.

Loaded the data using keras utils.


### 2.Preprocessing images for deep learning
Scaling images to (255,255,3).

Partitioning the dataset into train, validation and test set.


### 3.Creating a deep neural network classifier
Building the network using Sequential API and layers like Conv2D, maxpooling, Dense, Flatten.

We used relu and sigmoid activation function. 

Training the Deep Neural Network.

After running 20 epochs our model was able to give 99.5% accuracy.

Plotting model performance.


### 4.Evaluating model performance
Evaluating on the test partition - precision, recall and Binary accuracy.

Testing on new data.


### 5.Saving the model for deployment
Saving the model as h5.


