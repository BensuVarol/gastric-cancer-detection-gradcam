# Gastric Cancer Detection with Deep Learning and Grad-CAM

## Overview

This project focuses on gastric cancer histopathology image classification using deep learning. The main objective is to classify gastric tissue images as normal or abnormal and evaluate different convolutional neural network models for medical image analysis.

The project includes model training, evaluation, model comparison, and Grad-CAM visualization to improve interpretability. Grad-CAM is used to highlight image regions that contribute to the model’s prediction, making the results more understandable in a medical imaging context.

## Research Motivation

Histopathological image analysis plays an important role in cancer diagnosis and medical research. Deep learning methods can support image-based classification tasks by learning visual patterns from tissue images. However, in healthcare-related applications, model interpretability is also important.

This project explores both classification performance and visual explanation through Grad-CAM, providing a more complete workflow for medical image classification.

## Dataset

This project uses the GasHisSDB gastric cancer histopathology image dataset.

Raw image files are not included in this repository due to dataset size and data-sharing considerations. The notebook includes the dataset download and preparation steps needed to reproduce the workflow.

## Methodology

The project workflow includes:

* Dataset download and preparation
* Image preprocessing
* Train, validation, and test split creation
* Class imbalance handling using class weights
* Deep learning model training
* Model evaluation using accuracy, confusion matrix, and ROC curve
* Comparison of multiple CNN-based models
* Grad-CAM visualization for explainability

## Models Used

The following models are included in the project:

* Custom CNN
* ResNet50
* EfficientNetB0

These models are trained and evaluated to compare their performance on the gastric cancer classification task.

## Explainability

Grad-CAM is used to visualize important regions in histopathology images that influence the model’s predictions. This helps provide a visual interpretation of the classification results and supports a more transparent medical AI workflow.

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* OpenCV
* Google Colab

## Project Structure

```text
gastric-cancer-detection-gradcam/
├── README.md
├── requirements.txt
├── notebooks/
│   └── gastric_cancer_detection_gradcam.ipynb
├── data/
│   └── README.md
└── results/
    └── README.md
```

## Author

**Bensu Varol**
MSc Computer Engineering Student

Research interests: Machine Learning, Deep Learning, Medical Image Analysis, Computer Vision, and Explainable AI
