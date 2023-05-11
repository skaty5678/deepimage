# Image Classification with TensorFlow

This code demonstrates the process of training an image classification model using TensorFlow and performing inference on new images.

## Prerequisites

- TensorFlow
- Matplotlib
- OpenCV (cv2)

## Installation

1. Install the required dependencies by running the following command:
    !pip install tensorflow matplotlib opencv-python

## Usage

1. Preprocess the dataset:
- Remove images with unsupported file extensions.
- Normalize the pixel values of the images.
- Split the dataset into training, validation, and test sets.

2. Build the model:
- Create a sequential model using the `Sequential` class from TensorFlow.
- Add convolutional and pooling layers to the model.
- Flatten the output and add dense layers.
- Compile the model with appropriate loss and metrics.

3. Train the model:
- Fit the model on the training set.
- Monitor the validation loss and accuracy during training.
- Save the best model checkpoints.

4. Evaluate the model:
- Calculate precision, recall, and accuracy metrics on the test set.
- Display the evaluation results.

5. Perform inference on new images:
- Load the saved model.
- Read and resize the new image.
- Perform classification using the trained model.

6. Save the trained model:
- Save the trained model to a file for future use.



