# Tom and Jerry Image Classification

## Overview  
This project aims to develop a machine learning model capable of classifying images based on the presence of characters from the popular animated series *Tom and Jerry*. Instead of using Convolutional Neural Networks (CNNs), we focus on manually extracting features from the images, converting them into a structured dataset, and then applying traditional machine learning techniques for classification.

## Classification Categories  
Each image is classified into one of the following categories:  
- **Tom** – The image contains only Tom.  
- **Jerry** – The image contains only Jerry.  
- **Both** – The image contains both Tom and Jerry.  
- **None** – The image contains neither Tom nor Jerry.  

## Methodology  
1. **Feature Extraction**: Instead of deep learning, we manually extract key image features such as color histograms, texture descriptors, edge detection metrics, and other relevant visual properties.  
2. **Data Transformation**: The extracted features are stored in a structured DataFrame (DF) for further analysis.  
3. **Model Training**: Various traditional machine learning classifiers (e.g., SVM, Random Forest, k-NN) are trained on the extracted feature set.  
4. **Evaluation**: The model's performance is assessed using appropriate metrics such as accuracy, precision, recall, and F1-score.

## Dataset  
The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/balabaskar/tom-and-jerry-image-classification). It contains labeled images of Tom, Jerry, both characters together, and unrelated images for classification.

## Goals  
- Develop an efficient image classification pipeline without relying on deep learning.  
- Identify the most effective hand-crafted features for distinguishing between the four categories.  
- Compare the performance of different machine learning models on the extracted features.
