# Image Classification Using CNN on MNIST Dataset

## Objective

The objective of this project is to develop an image classification model using Convolutional Neural Networks (CNN) to recognize handwritten digits from the MNIST dataset.

## Tools and Technologies

* Python
* TensorFlow/Keras
* Google Colab
* NumPy
* Matplotlib
* Scikit-learn
* Seaborn

## Dataset

MNIST handwritten digit dataset consisting of 70,000 grayscale images of digits (0–9).

## Methodology

1. Load and preprocess the MNIST dataset.
2. Visualize sample images.
3. Normalize pixel values.
4. Build a CNN model.
5. Train the model using the training dataset.
6. Evaluate model performance.
7. Generate predictions on custom images.
8. Analyze results using a confusion matrix.

## Model Architecture

* Conv2D (32 filters)
* MaxPooling2D
* Conv2D (64 filters)
* MaxPooling2D
* Flatten Layer
* Dense Layer (128 neurons)
* Dropout Layer
* Output Layer (10 neurons with Softmax)

## Results

* Training Accuracy: Approximately 99%
* Test Accuracy: Approximately 98%

## Conclusion

The CNN model successfully classified handwritten digits with high accuracy. The project demonstrates the effectiveness of deep learning techniques for image classification tasks.
