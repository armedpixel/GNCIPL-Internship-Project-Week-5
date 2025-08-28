# Crop Type Classification – GNCIPL Internship Project (Week 5)
This project builds an artificial neural network (ANN) to classify crop types based on tabular agricultural features. It is part of the GNCIPL internship series and demonstrates a full machine learning pipeline—from preprocessing and model training to evaluation and visualization.

- Objective :
To develop a robust multi-class classifier that predicts crop types using structured agricultural data. The model aims to assist agronomists and planners in identifying suitable crops based on soil and environmental features.

- Model Overview :
  
  Architecture: Fully connected ANN with ReLU activations and dropout regularization

  Loss Function: sparse_categorical_crossentropy

  Optimizer: Adam

  Evaluation Metrics: Accuracy, confusion matrix, classification report

- Dataset
  
  Source: [Crop Recommendation Dataset on Kaggle](https://www.kaggle.com/datasets/irakozekelly/crop-recommendation-dataset/code)

  Features: Soil properties, climate indicators, and other agronomic variables

  Target: crop_label (multi-class categorical)
