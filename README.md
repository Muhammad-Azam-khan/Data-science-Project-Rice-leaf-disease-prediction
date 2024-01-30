**Rice Leaf Disease Prediction Project**

## Introduction

The project focuses on addressing the impact of bacterial, viral, and fungal diseases on rice leaf health, ultimately affecting rice production. By leveraging a dataset of rice leaf disease images, Convolutional Neural Network (CNN) models are trained to identify three prevalent rice leaf diseases: Bacterial Blight, Blast, and Brown Spot.

## Dataset

The dataset, sourced from Kaggle, comprises images of rice leaves affected by various diseases. The goal is to develop CNN models capable of accurately classifying these diseases, contributing to early detection and intervention in the agricultural sector.

## Instructions for Running Python Notebooks Locally

1. **Requirements:**
   - Ensure the necessary dependencies are installed by using the `requirements.txt` file.

2. **Platform Options:**
   - The project can be executed on Google Colab, Jupyter Notebook, or a local Python environment.

3. **Project Steps:**
   - The project is organized into multiple steps, including data augmentation, data splitting into training and testing sets, and model building.

## Data Augmentation & Split Data (Train, Test Set)

1. **Data Augmentation:**
   - Augmenting the dataset to introduce variety in each image, enhancing the model's ability to generalize.

2. **Data Splitting:**
   - Divide the augmented data into training and testing sets, crucial for evaluating model performance.

## Model Building

1. **Architecture:**
   -Here's a textual representation of the model architecture based on my code:

```plaintext
Model Architecture:

- Input Layer:
  - Shape: (IMAGE_SIZE, IMAGE_SIZE, CHANNELS)

- Convolution Layer 1 (Conv1):
  - Filters: 32
  - Kernel Size: (3, 3)
  - Padding: 'same'
  - Activation: 'relu'

- Max Pooling Layer 1 (Pooling1):
  - Pool Size: (2, 2)

- Convolution Layer 2 (Conv2):
  - Filters: 64
  - Kernel Size: (3, 3)
  - Padding: 'same'
  - Activation: 'relu'

- Max Pooling Layer 2 (Pooling2):
  - Pool Size: (2, 2)

- Convolution Layer 3 (Conv3):
  - Filters: 64
  - Kernel Size: (3, 3)
  - Padding: 'same'
  - Activation: 'relu'

- Max Pooling Layer 3 (Pooling3):
  - Pool Size: (2, 2)

- Dense Layer 1 (Dense1):
  - Neurons: 500
  - Activation: 'relu'

- Dropout Layer 1:
  - Rate: 0.3

- Dense Layer 2 (Dense2):
  - Neurons: 3 (num_classes)
  - Activation: 'softmax'

- Output Layer:
  - Activation: 'softmax'
```

This represents the sequential architecture of your Convolutional Neural Network (CNN) for rice leaf disease prediction. Adjustments can be made based on specific requirements or optimization needs.

2. **Training:**
   - Train the model on the augmented and split dataset to learn disease classification patterns.

3. **Prediction:**
   - Utilize the trained model to predict rice leaf diseases, contributing to early diagnosis and effective agricultural practices.
