# Fashion MNIST Classification with CNN

This project demonstrates how to use **Convolutional Neural Networks (CNNs)** to classify images from the **Fashion MNIST** dataset. The goal is to predict the clothing item shown in an image from 10 different categories.

### Dataset:
The Fashion MNIST dataset contains 60,000 training images and 10,000 test images of clothing items, including T-shirts, trousers, dresses, shoes, and more. Each image is 28x28 pixels in grayscale.

### Project Overview:
This notebook uses TensorFlow and Keras to build a simple CNN model for classifying the Fashion MNIST images into one of the following 10 categories:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

### Steps Involved:
1. **Data Preprocessing**: 
   - Load the Fashion MNIST dataset.
   - Normalize pixel values to a [0, 1] range.
   - Add a channel dimension to make the data suitable for Conv2D layers.

2. **Model Building**: 
   - A CNN with two convolutional layers, followed by max-pooling layers.
   - A fully connected layer for classification and a softmax output layer.

3. **Model Training**:
   - Use **Adam** optimizer and **sparse categorical cross-entropy loss** for training.
   - Train the model on the training set and validate on a validation split.

4. **Model Evaluation**:
   - Evaluate the model's performance on the test set.
   - Visualize training accuracy and loss curves.

5. **Predictions and Error Analysis**:
   - Generate predictions for test data.
   - Plot a confusion matrix to analyze model performance.

6. **Visualize Some Predictions**:
   - Display some sample images along with predicted and actual class labels.

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib
- scikit-learn
