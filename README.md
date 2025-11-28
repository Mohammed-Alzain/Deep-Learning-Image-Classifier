# Deep-Learning-Image-Classifier
🩺 Pneumonia Detection Using ResNet18 (Chest X-ray Classification)

This project implements a deep learning model based on ResNet18 to classify chest X-ray images as Pneumonia or Normal.
The goal is to demonstrate how convolutional neural networks can assist in medical image analysis for educational and research purposes.

🚀 Overview

Chest X-ray imagery is one of the most commonly used tools in diagnosing pneumonia.
This project uses a ResNet18 CNN architecture, trained on a labeled dataset of chest X-rays, to automatically detect pneumonia from input images.

The system takes a chest X-ray as input and outputs:

Prediction: Pneumonia / Normal

Confidence score (probability)

🧠 Model Architecture

Base model: ResNet18

Modified final layer for binary classification

Pretrained on ImageNet (optional), then fine-tuned on chest X-ray dataset

Loss function: Cross-Entropy

Optimizer: Adam or SGD

Augmentations: random horizontal flip, normalization, resizing, etc.

📊 Dataset

The model is trained on a publicly available chest X-ray dataset such as:

Kaggle: Chest X-Ray Images (Pneumonia)
or any similar dataset

Dataset includes:

Normal chest X-rays

Pneumonia chest X-rays (viral & bacterial)

All images are preprocessed to a consistent input size (e.g., 224×224).

📈 Training

Key steps:

Split into train / validation / test sets

Apply augmentations to improve generalization

Train for multiple epochs until validation stabilizes

Save best-performing model weights

Metrics tracked:

Accuracy

Loss

Precision, recall, F1-score

Confusion matrix
