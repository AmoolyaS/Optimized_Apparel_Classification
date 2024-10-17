# Optimized Apparel Image Classification using CNN

This project focuses on classifying images of apparel using Convolutional Neural Networks (CNN). The goal is to optimize the image classification model to accurately distinguish between different types of clothing items.

## Project Overview

- **Model**: Convolutional Neural Network (CNN)
- **Dataset**: Fashion MNIST dataset, containing 60,000 training images and 10,000 test images of 10 different apparel categories.
- **Objective**: Build and optimize a deep learning model to classify apparel images with high accuracy.

## Key Features

1. **Data Preprocessing**:
   - Normalization of pixel values to scale the images.
   - Reshaping the data to feed it into the CNN model.
   - Splitting the dataset into training and testing sets.

2. **Model Architecture**:
   - Multiple convolutional and pooling layers to capture image features.
   - Dropout layers to prevent overfitting.
   - Fully connected layers to make final predictions.
   - Softmax activation for multi-class classification.

3. **Optimization**:
   - Use of **Adam** optimizer for faster convergence.
   - **Categorical Crossentropy** as the loss function.
   - Hyperparameter tuning to achieve better performance.

4. **Performance Evaluation**:
   - Accuracy and loss metrics are tracked during training.
   - Confusion matrix and classification report generated for the test set to evaluate the model's performance.

## Results

- **Accuracy Achieved**: The model was able to achieve an accuracy of over 90% on the test set.
- **Loss**: The model's loss decreased steadily during training, indicating proper learning.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/AmoolyaS/Optimized_Apparel_Image_Classification.git
