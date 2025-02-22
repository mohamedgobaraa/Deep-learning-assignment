# Alzheimer's MRI Classification

## Overview
This project is an advanced deep learning pipeline for classifying Alzheimer's disease using MRI scans. The model categorizes brain images into different stages of dementia, leveraging convolutional neural networks (CNNs) and TensorFlow/Keras.

This assignment was conducted under the supervision of **Dr. Noha Alattar** as part of a deep learning course.

## Dataset
The dataset used in this project is an **Augmented Alzheimer's MRI Dataset**, containing MRI images categorized into:
- **Non-Demented**
- **Mild Demented**
- **Moderate Demented**
- **Very Mild Demented**

The dataset is preprocessed and split into **training, validation, and test sets** for robust model evaluation.

## Installation & Usage
### Requirements
Ensure you have the following dependencies installed:
```bash
pip install tensorflow pandas numpy matplotlib seaborn scikit-learn
```

### Running the Notebook
1. Download the dataset and update the path in the notebook.
2. Run the preprocessing steps to prepare the data.
3. Train the XceptionNet model and evaluate its performance.
4. Visualize results using Matplotlib and Seaborn.

## Evaluation Metrics
The model is evaluated using:
- **Accuracy**
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-Score)**

## Results
- The model achieves a high classification accuracy on the test set.
- Loss and accuracy plots are provided to analyze model performance.
- Confusion matrix visualization helps assess misclassifications.

## References
- [Original Dataset Source](https://www.kaggle.com/datasets/uraninjo/augmented-alzheimer-mri-dataset)

## Acknowledgment
This work was completed as an assignment under **Dr. Noha Alattar** for the deep learning course.

