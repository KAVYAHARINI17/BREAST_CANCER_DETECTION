# BREAST_CANCER_DETECTION
This project implements a deep learning model to classify breast tumors as malignant or benign using neural networks. It utilizes the Wisconsin Breast Cancer Dataset, containing 30 features derived from cell nuclei images.
<br>
The model is a multi-layer perceptron (MLP) designed to predict tumor malignancy based on 569 samples with 30 features. The dataset is preprocessed and split for training and testing. Performance is measured using accuracy, precision, recall, and F1-score.
<br>

Key Features
Deep Learning Model: Fully connected neural network (MLP).
Dataset: Wisconsin Breast Cancer Dataset with 30 features.
Preprocessing: Data normalization using StandardScaler.
Performance Metrics: Accuracy, precision, recall, and F1-score.
Predictive System: Classifies tumors as malignant or benign.

Workflow
Preprocessing:
Normalize features using StandardScaler.
Split data into 80% training and 20% testing.

Model Training:
Build MLP with ReLU activation and Softmax output.
Train using Adam optimizer and binary cross-entropy loss.
Evaluation:

Evaluate using accuracy, precision, recall, F1-score, confusion matrix, and classification reports.
Prediction System:

Input data is passed to the trained model for tumor classification (malignant/benign).
