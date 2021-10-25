# MNIST-dataset-Classification using Keras
## Dataset
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems.
The MNIST database of handwritten digits, has a training set of 60,000 28x28 grayscale images of the 10 digits, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.<br/>
Sample images from MNIST test dataset:<br/>

![github-small](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

## Image classification Convolutional Neural Network (CNN) model on MNIST dataset
The model consists of 4 convolutional layers. Each of these convolutional layers are followed by a MaxPooling layer, a Droput layer and Batch normalization. The output of the earlier layers if flattened followed by 3 dense layers which have their own dropout and Batch normalization layers. The final layer consists of a dense layer with 10 neurons and soft-max activation to give the final ouput (prediction).

## Implementation accuracy
Train accuracy: 99.51%<br/>
Test accuracy: 99.51%<br/>

## The following additional plots and charts were made to understand the model beter.
Loss vs Epochs

Accuracy vs Epochs

Confusion Matrix -- "Truth" stands for the actual value of the classification type whereas "predicted" stands for the predicted classification by the model.
