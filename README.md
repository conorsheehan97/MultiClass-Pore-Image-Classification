# MultiClass-Pore-Image-Classification
This project investigates the ability of a Convolutional Neural Network model to differentiate between 600 images of 3 different classes of pores.

For this body of work 200 seperate images of 3 classes of pores were obtained, and manually labelled from microscope images. We want to see how good a CNN can classify these images, similar to how our own neurons did. For this, a CNN model consisting of convolutional layers, max pooling layers, random dropout layers, and fully connected layers was put together. We also used callback, which reduces the learning rate in case of no improvement, or just simply stops it. We then split our data into an 80/20 split, trained the model on an augmented training set. 

We plotted our Training/Validation Loss/Accuracy, and then tested our final model on the test set we initially hid from the model. A confusion matrix was also used in order to compare what the model misclassified as what. 

Models used: Convolutional Neural Network

Libraries used: Pandas, Numpy, Tensorflow, Keras, Scikitlearn, Matplotlib, Path, Random,
