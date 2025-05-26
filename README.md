# fakeddit_cnn_classifier
CNN-based 6-Class Fake News Detection using Fakeddit Images

This project aims to classify images from the Fakeddit dataset into six distinct categories of misinformation using a Convolutional Neural Network (CNN). The goal is to help detect various types of misleading or manipulated content in online media through automated image classification.

# Dataset
Dataset: Fakeddit Dataset

Subset: multimodal_only_samples

Preprocessing Steps:

Image resizing to 256x256 pixels

Normalization using mean=0.5, std=0.5

Removal of corrupt or missing images

# Categories:
index [0] TRUE

index [1] SATIRE

index [2] FALSE CONNECTION

index [3] IMPOSTER CONTENT

index [4] MANIPULATED CONTENT

index [5] MISLEADING CONTENT

# Training Information

Epochs: 30

Optimizer: Adam (Learning rate = 1e-3)

Loss Function: CrossEntropyLoss

Train Accuracy: 99%

Validation Accuracy: ~52%

Observations: The model currently shows significant overfitting, indicated by high training accuracy and low validation accuracy. This suggests the need for more robust regularization or advanced models like pretrained CNNs.

# Results Visualization

Accuracy and Loss Trends: Displays training and validation accuracy and loss over epochs.

Confusion Matrix: Visual representation of prediction accuracy for each class.

Prediction Examples: Images showing correct and incorrect predictions.

# How to Run (Kaggle Environment)

This project was developed and executed in the Kaggle notebook environment. To run this project:

Copy the notebook.

Before run this ensure the dataset Fakeddit Dataset(https://www.kaggle.com/datasets/vanshikavmittal/fakeddit-dataset) is downloaded in your input section.



