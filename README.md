## Digit Classifier
A deep learning project to classify handwritten digits using a Convolutional Neural Network (CNN) in Keras and TensorFlow.

## Project Overview
This project demonstrates a digit classification model built with Python, Keras, and TensorFlow. The model is trained on the MNIST dataset, a popular dataset for handwritten digit recognition, which contains 60,000 training images and 10,000 test images of digits from 0 to 9. The trained model can classify any digit image from this dataset with high accuracy.

## Key Features
- Model Architecture: Utilizes a Convolutional Neural Network (CNN) with layers such as Flatten, Dense, and Softmax for accurate classification.

- Dataset: MNIST, containing grayscale images of size 28x28 pixels, each labeled with the corresponding digit.

- Training and Evaluation: The model is trained for 10 epochs, with a validation split to monitor accuracy and performance.

- Prediction: Supports making predictions on new handwritten digit images, utilizing the predict method and extracting class predictions with argmax.

## Dependencies
- Python 3.x
- TensorFlow and Keras
- NumPy
- Matplotlib (for visualizing predictions)

