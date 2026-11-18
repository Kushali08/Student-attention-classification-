# Student-attention-classification-
A Deep Learning-based Student Attention Classification system that analyzes classroom images using visual features such as head orientation, eye alignment, back posture, and hand movements to classify students into Attentive, Neutral, and Inattentive categories using multiple CNN architectures.
# Deep Learning-Based Student Attention Classification Using Multi-Model Visual Features

## Project Overview

This project focuses on developing a deep learning-based system to automatically classify student attention levels using classroom images.

The system analyzes visual features such as head orientation, eye alignment, back posture, and hand movements to identify student attention levels.

Students are classified into three categories:
- Attentive
- Neutral
- Inattentive

The project compares multiple deep learning architectures to identify effective models for student attention classification.

## Objectives

- To develop an automated student attention classification system.
- To analyze student behavior using classroom images.
- To identify visual features related to student attention.
- To train and compare multiple deep learning models.
- To evaluate model performance using different evaluation metrics.

## Dataset

The dataset consists of approximately 500 images collected from a real classroom environment during lectures.

The images are categorized into three classes:

1. Attentive – Students facing the lecture and showing focused posture.
2. Neutral – Students showing a moderate or passive level of attention.
3. Inattentive – Students looking away from the lecture or displaying distracted posture.

## Visual Features

The system considers the following visual features:

- Head Orientation
- Eye Alignment
- Back Posture
- Hand Movements

## Technologies Used

**Programming Language:**
- Python

**Deep Learning Frameworks:**
- TensorFlow
- Keras
- PyTorch

**Libraries:**
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

**Development Environment:**
- Jupyter Notebook
- Google Colab

## Deep Learning Models

The following models were trained and evaluated:

1. EfficientNet-B0
2. EfficientNet-B1
3. ResNet-18
4. ResNet-34
5. ResNet-50
6. DenseNet-121
7. MobileNetV2
8. ShuffleNetV2
9. SqueezeNet 1.1

## Methodology

The project follows these major steps:

1. Dataset Collection
2. Data Preprocessing
3. Image Resizing
4. Image Normalization
5. Data Augmentation
6. Feature Extraction
7. Model Training
8. Attention Classification
9. Model Evaluation

## Model Training Configuration

- Optimizer: Adam
- Loss Function: Categorical Cross-Entropy
- Batch Size: 32
- Epochs: 20–30
- Learning Rate: 0.001
- Training Approach: Transfer Learning

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Cohen's Kappa
- Confusion Matrix

## Results

Among the evaluated models, EfficientNet-B1 achieved the best overall performance according to the project findings.

Lightweight architectures such as MobileNetV2 and ShuffleNetV2 also demonstrated good performance with lower computational requirements.

## Applications

- Smart Classroom Systems
- Student Engagement Analysis
- Educational Data Analytics
- Classroom Monitoring Support
- Data-Driven Teaching Improvements

## Future Enhancements

- Real-time classroom attention monitoring.
- Integration of video-based analysis.
- Emotion detection.
- Advanced AI model integration.
- Improved student behavior analysis.

## Conclusion

This project demonstrates how deep learning and computer vision techniques can be used to analyze student attention through classroom images. By comparing multiple CNN architectures, the system identifies effective approaches for classifying student attention levels.

The proposed system can support teachers in understanding classroom engagement and contribute to the development of smart educational environments.

## Author

**Meesala Kushali**

B.Sc Honours – Data Science

Bhavan's Vivekananda College of Science, Humanities & Commerce

Academic Year: 2025–2026
