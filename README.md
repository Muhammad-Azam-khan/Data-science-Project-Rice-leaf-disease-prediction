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
   - The model architecture consists of:
     - Input Layer
     - Convolution Layer 1 (Conv1)
     - Max Pooling Layer 1 (Pooling1)
     - Convolution Layer 2 (Conv2)
     - Max Pooling Layer 2 (Pooling2)
     - Convolution Layer 3 (Conv3)
     - Two Dense Layers (Dense1, Dense2)
     - Output (Softmax) Layer

2. **Training:**
   - Train the model on the augmented and split dataset to learn disease classification patterns.

3. **Prediction:**
   - Utilize the trained model to predict rice leaf diseases, contributing to early diagnosis and effective agricultural practices.
