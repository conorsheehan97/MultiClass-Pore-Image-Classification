# MultiClass-Pore-Image-Classification
## Overview
This project investigates the classification ability of a Convolutional Neural Network (CNN) model to differentiate between 600 images of pores belonging to 3 different classes. The images were manually labeled from microscope images, totaling 200 images per class. The goal is to evaluate how well the CNN can classify these images, similar to human neuron classification abilities.

## Methodology
### Data Collection and Labeling:
- Obtained 200 images per class of pores from microscope images and manually labeled them.

### Model Architecture:
 - Built a CNN model consisting of convolutional layers, max pooling layers, random dropout layers for regularization, and fully connected layers for classification.

### Training Strategy:
 - Utilized callbacks to adjust learning rate on plateau or early stopping.
 - Split data into 80/20 train-test sets and trained the model on an augmented training set to enhance generalization.

### Evaluation:
 - Plotted Training/Validation Loss and Accuracy curves to monitor model performance.
 - Evaluated the final trained model on a previously unseen test set.
 - Generated a confusion matrix to analyze classification errors and understand which classes the model misclassified.

### Models Used
 - Convolutional Neural Network (CNN)

### Libraries Used
 - Pandas
 - Numpy
 - Tensorflow
 - Keras
 - Scikit-learn
 - Matplotlib
 - Path (for file handling)
 - Random (for data augmentation)

## Conclusion
This project demonstrates the application of a Convolutional Neural Network to classify pores in microscope images based on manually labeled data. By leveraging CNN architecture and training strategies, we achieved promising classification results. The use of augmentation techniques and callback functions enhanced model robustness and performance evaluation. Future work may involve fine-tuning the model architecture or exploring other deep learning techniques for further improvement.

Contributions and feedback are welcome to enhance this project's capabilities and insights into automated classification tasks in microscopy.
