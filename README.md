# SmartVision: Deep Learning Image Classification Using CNNs

A Deep Learning project developed as part of the CSE422 course at Lovely Professional University (LPU), focused on image classification using Artificial Neural Networks (ANNs), Convolutional Neural Networks (CNNs), and TensorFlow/Keras.

## Project Overview

SmartVision is an image classification system designed to recognize and categorize images using deep learning techniques. The project explores how neural networks learn features from image data, how backpropagation optimizes model parameters, and how CNN architectures improve image classification performance.

The application aims to provide an interactive interface where users can upload images, view predicted classes, and explore model performance.

**Project Status:** Under Development

## Objectives

- Understand the fundamentals of artificial neural networks and perceptrons.
- Implement feedforward propagation in neural networks.
- Demonstrate backpropagation and gradient descent for model training.
- Build a CNN for image classification.
- Understand convolution, stride, padding, pooling, and feature maps.
- Evaluate classification models using standard performance metrics.
- Explore transfer learning using pretrained models such as VGG16.
- Develop an interactive interface for image classification and model evaluation.
- Explore recurrent neural networks, LSTMs, and GRUs through supporting experiments.

## Course Outcomes Alignment

This project supports the following CSE422 course outcomes:

| Course Outcome | Implementation |
|---|---|
| CO1 | Perceptron models for binary and multiclass classification |
| CO2 | Information flow and dimensionality transformations in neural networks |
| CO3 | Backpropagation and gradient descent for model training |
| CO4 | CNN architecture and image classification |
| CO5 | Image classification using Python and TensorFlow/Keras |
| CO6 | Supporting experiments involving RNNs, LSTMs, and GRUs |

The final coverage of each outcome will depend on the experiments implemented and evaluated.

## Key Features

### 1. Image Classification
- Upload images for classification.
- Preprocess images before model inference.
- Display predicted classes and model confidence scores.
- Explore image classification using a trained CNN.

### 2. Neural Network Experiments
- Implement perceptron models.
- Demonstrate feedforward propagation.
- Explore activation functions such as sigmoid and ReLU.
- Examine network weights, biases, and dimensionality.

### 3. CNN Architecture
- Implement convolutional layers.
- Explore stride and padding.
- Visualize feature maps.
- Understand max pooling and flattening.
- Examine the flow of information through CNN layers.

### 4. Model Training
- Train neural networks using backpropagation.
- Experiment with gradient descent and optimizers.
- Monitor training and validation loss.
- Compare training configurations.

### 5. Model Evaluation
- Calculate accuracy, precision, recall, and F1-score.
- Generate confusion matrices.
- Analyze class-wise performance.
- Compare different model architectures.

### 6. Transfer Learning
- Explore pretrained CNN architectures such as VGG16.
- Compare transfer learning with a CNN trained from scratch.
- Evaluate the impact of model architecture on classification performance.

### 7. Supporting Sequence-Modelling Experiments
- Explore recurrent neural networks.
- Understand vanishing and exploding gradients.
- Experiment with LSTM and GRU architectures.
- Demonstrate sequence prediction.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Primary programming language |
| TensorFlow | Deep learning framework |
| Keras | Neural network model development |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| scikit-learn | Model evaluation |
| Streamlit | Interactive web interface |
| Jupyter Notebook | Experimentation and analysis |
| Git and GitHub | Version control and project hosting |

## Dataset

The project is intended to use the CIFAR-10 dataset for image classification.

CIFAR-10 contains 60,000 colour images across 10 classes:

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

Each image has a resolution of 32 × 32 pixels.

The dataset can be loaded using TensorFlow/Keras. Additional datasets may be used for supporting experiments.

Dataset documentation:
https://www.tensorflow.org/api_docs/python/tf/keras/datasets/cifar10

## Project Architecture

The planned image classification workflow is:

Input Image
    |
    v
Image Preprocessing
    |
    v
Convolutional Layer
    |
    v
ReLU Activation
    |
    v
Pooling Layer
    |
    v
Additional Convolutional Layers
    |
    v
Flatten Layer
    |
    v
Dense Layer
    |
    v
Output Layer
    |
    v
Predicted Class

## Installation and Setup

### Prerequisites

- Python 3.10 or another Python version supported by your selected TensorFlow release.
- pip
- Git
- A code editor such as VS Code or Jupyter Notebook.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Cse-422.git
cd Cse-422
