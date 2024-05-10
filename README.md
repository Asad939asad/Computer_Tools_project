# Malaria Classification Using CNN
### Overview
This repository contains a Python script that uses deep learning to classify images of malaria-infected blood cells into two classes: parasitized and uninfected. The model is trained on the Malaria dataset from TensorFlow Datasets and uses convolutional neural networks (CNNs) to make predictions.
### Installation
To run this code, you will need to have Python 3.6 or later installed on your machine. Additionally, you will need to install the necessary libraries:

    TensorFlow
    TensorFlow Datasets
    Matplotlib
    PIL (Python Imaging Library)

You can install these libraries using pip:

pip install tensorflow tensorflow-datasets matplotlib pillow

### Usage
To use this code, simply run the Python script. The script will download the Malaria dataset, preprocess the images, split the data into training and testing sets, train a CNN model, and then use the trained model to make predictions on a test image.
### Configuration
The script is configured to use the following settings:

    The Malaria dataset is loaded from TensorFlow Datasets.
    The training set is shuffled and split into batches of 16 images.
    The model is trained for 10 epochs.
    The model is evaluated on the test set after training.

### Output
The script will print the predicted class for the test image and display the image with the predicted class label.
### Contributing
Contributions are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
