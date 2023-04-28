# sEMG-Gesture-Classification Project

This project aims to build a classification model for sEMG (surface electromyography) signals to recognize hand gestures performed by individuals using machine learning techniques. The ultimate goal is to create a reliable and accurate classification model that can be used in real-world applications such as prosthetic control, human-robot interaction, and virtual reality.

## Data Acquisition
sEMG signals were collected from 6 participants while performing 6 different hand gestures. Each gesture was performed for 2 seconds.

## Preprocessing
The collected sEMG signals were preprocessed by filtering and cleaning to remove any noise or unwanted artifacts.

## Feature Extraction
Relevant features were extracted from the preprocessed sEMG signals to be used for classification.

## Handling Outliers
Various outlier handling and data transformation techniques were applied to the normalized DataFrame, including Interquartile Range (IQR), Z-score Standardization, Yeo-Johnson Transformation, Winsorization, Hampel Filter, and a combination of IQR and Z-score.

## Classification
Different machine learning models were developed and compared for classifying the hand gestures based on the extracted features, including KNN.

## Model Evaluation
The performance of the developed models was evaluated using metrics such as accuracy, precision, recall, and F1 score. The best accuracy achieved was 99% using the Z-score method.

## Hardware
The Grove EMG detector was used to collect sEMG signals, and an STM32 microcontroller was used to handle calculations required by the machine learning algorithm.

## Code
The code includes functions for data preprocessing, outlier handling, feature extraction, and classification. The code is provided in Python and can be easily adapted for different applications.

## Conclusion
This project demonstrates the feasibility of using sEMG signals and machine learning techniques for gesture recognition. The achieved accuracy of 99% using a smaller number of sensors is promising for real-world applications. The code and methods used in this project can be adapted for other similar projects or applications.
