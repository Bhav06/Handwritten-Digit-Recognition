# Handwritten Digit Recognition

## Project Overview

This project demonstrates the implementation of a Deep Learning model for handwritten digit recognition. A Convolutional Neural Network (CNN) is built and trained using the MNIST dataset to classify handwritten digits from 0 to 9.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras

## Dataset

The MNIST dataset is used in this project. It contains grayscale images of handwritten digits belonging to 10 classes, representing digits from 0 to 9.

Each image has a size of 28 × 28 pixels.

## Steps Performed

1. Imported the required Python libraries.
2. Loaded the MNIST handwritten digit dataset.
3. Explored and visualized sample digit images.
4. Normalized the image pixel values.
5. Reshaped the images for CNN input.
6. Converted digit labels into categorical format.
7. Built a Convolutional Neural Network (CNN).
8. Trained the model using the training dataset.
9. Evaluated the model on unseen test data.
10. Generated sample predictions for handwritten digits.
11. Created a classification report and confusion matrix.
12. Saved the trained model for future use.

## Model Architecture

The CNN model consists of:

- Convolutional layers for feature extraction
- Max Pooling layers for dimensionality reduction
- Flatten layer
- Dense layers for classification
- Dropout layer to reduce overfitting
- Output layer with 10 neurons for digit classification

## Key Features

- Handwritten digit classification
- MNIST dataset processing
- Image normalization
- CNN model implementation
- Model training and evaluation
- Sample digit predictions
- Classification report
- Confusion matrix
- Trained model saving

## Learning Outcomes

- Understanding image classification
- Working with the MNIST dataset
- Image preprocessing and normalization
- Building a Convolutional Neural Network
- Training and evaluating a Deep Learning model
- Making predictions on unseen handwritten digit images

## Conclusion

This project demonstrates the practical implementation of Deep Learning for handwritten digit recognition. A Convolutional Neural Network was built and trained using the MNIST dataset to classify handwritten digits from 0 to 9.

The model was evaluated using unseen test images, and its performance was analyzed using accuracy, loss, a classification report, and a confusion matrix. Sample predictions also demonstrated the model's ability to correctly recognize handwritten digits.

This project shows how Convolutional Neural Networks can effectively learn image features and perform accurate image classification. Such technology can be applied in automated form processing, postal code recognition, bank cheque processing, and other computer vision systems.
