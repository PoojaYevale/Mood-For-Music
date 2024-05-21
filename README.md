# Emotion Recognition and Music Recommendation System

This project leverages Convolutional Neural Networks (CNN) and ResNet50V2 for facial emotion recognition from images. Based on the predicted emotion, the system recommends a list of songs to match the detected mood.
# Table of Contents
1.Project Overview

2.Dataset

3.Model Architecture

4.Training

5.Evaluation

6.Visualizations

7.Music Recommendation

# Project Overview
The goal of this project is to classify facial expressions into seven categories: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise. Based on the predicted emotion, the system recommends music that matches the emotion.
# Dataset
The dataset used for this project is a collection of facial expression images, divided into training and testing sets. Each image is labeled with one of the seven emotions.
# Model Architecture
# CNN Model
The CNN model is a simple convolutional neural network designed to recognize emotions from facial expressions.

# ResNet50V2 Model
ResNet50V2 is a pre-trained deep convolutional network used for transfer learning. It is fine-tuned on our facial expression dataset to improve accuracy.

# Training
Both models are trained on the facial expression dataset with the following configurations:

Image Size: 224x224 pixels

Batch Size: 64

Optimizer: Adam

Loss Function: Categorical Cross-Entropy

Training involves data augmentation to improve the robustness of the models.


# Evaluation
The models are evaluated on a test dataset. Metrics such as loss and accuracy are used to measure performance. Confusion matrices are plotted to visualize the classification results.


# Visualizations
Training and validation loss and accuracy are plotted to understand the training process. Confusion matrices provide insights into the performance of the models on different emotions.

# Music Recommendation
Based on the predicted emotion, a list of songs is recommended. The songs are filtered based on their mood and popularity, providing the top 5 songs for each emotion.

