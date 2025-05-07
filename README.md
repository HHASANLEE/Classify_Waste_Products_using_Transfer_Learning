# Waste Classification Using Transfer Learning (VGG16)
This project uses transfer learning with the VGG16 model to classify different types of waste into categories like cardboard, glass, metal, paper, plastic, and trash. It aims to support smart recycling and waste management systems using AI.

## Overview
We use the VGG16 model, pre-trained on the ImageNet dataset, to build a classifier that recognizes six categories of waste. By reusing this model, we reduce training time while still achieving good performance.

## Technologies Used
Python 🐍

TensorFlow & Keras 🧪

Transfer Learning (VGG16)

Google Colab 💻

NumPy, Matplotlib, Pandas 📊

## Dataset
The dataset contains images labeled and stored in folders:

Cardboard

Glass

Metal

Paper

Plastic

Trash

The images are divided into training and testing sets.

## How It Works
Load and Preprocess Data

Images are resized to 224x224 (VGG16 input size).

Pixel values are normalized.

Apply Transfer Learning with VGG16

Load VGG16 without the top (fully connected) layers.

Freeze its weights to keep pre-trained features.

Add new dense layers for our 6 waste categories.

Train the Model

The model is trained on the dataset.

Accuracy and loss during training are visualized.

Evaluate and Predict

The model is tested on unseen images.

Predictions are compared with actual labels.

## Results
The model performs well in identifying waste types.

This approach is useful for automating waste sorting systems.

## How to Run
Open the notebook: Classify_Waste_Products_using_Transfer_Learning.ipynb in Google Colab.

Upload your dataset (organized into folders by class).

Run all cells.

Check training results and predictions.
