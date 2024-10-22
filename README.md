# Skin Cancer Detection Model

## Introduction

Skin cancer is one of the most common types of cancer, and early detection is crucial for effective treatment. This project aims to leverage deep learning techniques, specifically CNNs, to analyze skin images and classify them into different types of lesions, including benign and malignant categories.

## Dataset

The model is trained on the **ISIC Skin Cancer Dataset** available on Kaggle. The dataset contains a diverse range of skin lesion images labeled according to their categories, facilitating supervised learning.
- **Dataset Link**: [ISIC Skin Cancer Dataset](https://www.kaggle.com/datasets/rm1000/skin-cancer-isic-images)

## Model Architecture

The CNN architecture consists of several convolutional layers followed by activation functions, pooling layers, and fully connected layers. Key components include:

- **Convolutional Layers**: Extract features from the images.
- **Activation Functions**: ReLU (Rectified Linear Unit) is commonly used for introducing non-linearity.
- **Pooling Layers**: Max pooling is utilized to reduce dimensionality.
- **Dropout Layers**: Help prevent overfitting during training.

The specific architecture includes:

- Input Layer
- 2D Convolutional Layers
- Max Pooling Layers
- Dropout Layers
- Fully Connected Layers
- Output Layer with Softmax Activation

- ## Results

The model’s performance metrics include accuracy, precision, recall, and F1-score. The evaluation metrics can be visualized using:
- **Accuracy**: To test the accuracy of the model.
- **Confusion Matrix**: To visualize model predictions vs. actual labels.
- **ROC Curve**: To demonstrate model performance.
- **Sample Predictions**: Example images with the model's predicted labels.

## Installation

To run the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/HarshGosula/Skin-Cancer-Detection.git
