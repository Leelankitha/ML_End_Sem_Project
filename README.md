CNN-LSTM Model for Intrusion Detection Using UNSW-NB15 Dataset
This project implements a hybrid deep learning model combining Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks to detect network intrusions. The model is trained and evaluated on the UNSW-NB15 dataset, a comprehensive dataset for network intrusion detection research.

Introduction
The CNN-LSTM hybrid model aims to leverage the feature extraction capabilities of CNNs and the temporal sequence learning power of LSTMs to enhance the accuracy of intrusion detection systems (IDS). This approach helps in detecting various types of attacks and abnormal network behavior in a more robust manner.

Dataset
The UNSW-NB15 dataset consists of network traffic data labeled into different categories of normal and attack instances. It includes features extracted from real network traffic, along with metadata to aid in detecting intrusions. The dataset provides an extensive set of records with various types of attacks such as DoS, Fuzzers, Worms, and others.

Dataset Features:

49 attributes, including source/destination IPs, protocols, timestamps, and attack types.
Binary classification (Normal vs. Attack) or multi-class classification for different attack categories.
Model Architecture. The proposed model combines a Convolutional Neural Network (CNN) with a Long Short-Term Memory (LSTM) network:

CNN Layers: Extract spatial features from the network traffic data.
LSTM Layers: Learn the sequential patterns and temporal dependencies.
Dense Layers: Fully connected layers for final classification.
The architecture ensures that the model captures both the spatial correlations and sequential dependencies in the data, leading to more accurate detection.
