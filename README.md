# sEMG-Gesture-Classification


# sEMG Gesture Recognition Project

This repository contains code and analysis for a surface electromyography (sEMG) gesture recognition project. The project aims to classify hand gestures based on sEMG signals recorded from two channels.

## Dataset
The dataset used in this project consists of sEMG data collected from three participants performing a series of hand gestures. The gestures include:

Rest
Yumruk (Fist)
El dışarı (Hand outward)
El yukarı (Hand upward)
İçe bükme (Wrist inward)
El içeri (Hand inward)
Yumruk (Fist)
Additionally, the dataset was expanded to include tightened gesture data (zorlama), where the participants' hands were tightened during the trials. This new data provided more distinctive features for the classification algorithm.

## Methodology
The analysis involved preprocessing the raw sEMG data, including filtering and feature extraction. The following steps were performed:

- Bandpass filtering of the sEMG signals to focus on the frequency range of interest.
- Extraction of features, such as waveform length and slope sign changes, to capture essential characteristics of the sEMG signals.
- Division of the dataset into training and testing sets.
- Standardization of the features for more effective machine learning.
- Application of K-Nearest Neighbors (KNN) and Support Vector Machine (SVM) algorithms for gesture classification. (more to come)

## Results
The KNN classifier, when applied to the expanded dataset with tightened gesture data, achieved an accuracy of 82%. This is a significant improvement compared to the initial analysis without the tightened gesture data. The results indicate that the tightened gesture data provides more distinctive features, allowing for better differentiation between various hand gestures.

## Conclusion
The incorporation of tightened gesture data (zorlama) in the sEMG analysis led to a substantial improvement in the classification accuracy. This suggests that capturing more subtle differences in muscle activation patterns can provide additional information for the classifier to identify unique features across gestures.

Future work could explore additional feature extraction techniques, machine learning algorithms, or optimization strategies to further improve the classification accuracy. Investigating the impact of collecting more data from a larger number of participants, as well as exploring different types of gestures or variations in hand positions, would help in creating more generalizable and robust models for gesture recognition. Such improvements could contribute to the development of more accurate and reliable systems for controlling prosthetic limbs or other assistive devices.

