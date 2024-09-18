# BREAST_CANCER_DETECTION
This project implements a deep learning model to classify breast tumors as malignant or benign using neural networks. It utilizes the Wisconsin Breast Cancer Dataset, containing 30 features derived from cell nuclei images.
<br>
The model is a multi-layer perceptron (MLP) designed to predict tumor malignancy based on 569 samples with 30 features. The dataset is preprocessed and split for training and testing. Performance is measured using accuracy, precision, recall, and F1-score.
<br>
Key Features
Deep Learning Model: Fully connected neural network (MLP).
<br>
Dataset: Wisconsin Breast Cancer Dataset with 30 features.
<br>
Preprocessing: Data normalization using StandardScaler.
<br>
Performance Metrics: Accuracy, precision, recall, and F1-score.
<br>
Predictive System: Classifies tumors as malignant or benign.
<br>
Workflow
<br>
Preprocessing:
<br>
Normalize features using StandardScaler.
Split data into 80% training and 20% testing.
<br>

Model Training:
<br>
Build MLP with ReLU activation and Softmax output.
Train using Adam optimizer and binary cross-entropy loss.
<br>
Evaluation:
<br>
Evaluate using accuracy, precision, recall, F1-score, confusion matrix, and classification reports.
<br>
Prediction System:
<br>
Input data is passed to the trained model for tumor classification (malignant/benign).
<br>
Tools & Libraries:<br>
Keras/TensorFlow: For model building and training.<br>
Pandas & NumPy: Data manipulation and preprocessing.<br>
Matplotlib & Seaborn: Visualization.<br>
Scikit-learn: Preprocessing and performance metrics.<br>

