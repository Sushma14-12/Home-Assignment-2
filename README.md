# Home-Assignment-2
# Deep Learning Repository

## Overview
This repository contains implementations of various deep learning concepts and architectures using TensorFlow, Keras, NumPy, and OpenCV. It covers convolution operations, feature extraction, and CNN architectures such as AlexNet and ResNet.

## Contents
### Question 1: Cloud Computing for Deep Learning
- **(a) Elasticity & Scalability**: Definitions of elasticity and scalability in the context of cloud computing.
- **(b) Comparison of Cloud Services**: Comparison of AWS SageMaker, Google Vertex AI, and Microsoft Azure Machine Learning Studio.

### Question 2: Convolution Operations with Different Parameters
- Implementation of convolution operations using different strides and padding on a 5x5 input matrix with a 3x3 kernel.
- Outputs feature maps for the following configurations:
  - Stride = 1, Padding = ‘VALID’
  - Stride = 1, Padding = ‘SAME’
  - Stride = 2, Padding = ‘VALID’
  - Stride = 2, Padding = ‘SAME’

### Question 3: CNN Feature Extraction with Filters and Pooling
#### Task 1: Edge Detection Using Sobel Filter
- Applies Sobel filter for edge detection in x-direction and y-direction using OpenCV.
- Displays original image and filtered images.

#### Task 2: Max Pooling and Average Pooling
- Demonstrates max pooling and average pooling on a random 4x4 matrix.
- Outputs the original matrix, max-pooled matrix, and average-pooled matrix.

### Question 4: Implementing and Comparing CNN Architectures
#### Task 1: Implement AlexNet
- Implements a simplified AlexNet architecture using TensorFlow/Keras.
- Prints the model summary.

#### Task 2: Implement Residual Block and ResNet
- Defines a residual block function.
- Builds a simple ResNet-like model with residual connections.
- Prints the model summary.

## Dependencies
Ensure you have the following libraries installed:
```bash
pip install tensorflow numpy opencv-python
```

## Running the Scripts
Each script is structured to be executed independently. Use:
```bash
python script_name.py
```
Replace `script_name.py` with the relevant script file.

## Contributors
- Author: [Your Name]

## License
This project is licensed under the MIT License.
