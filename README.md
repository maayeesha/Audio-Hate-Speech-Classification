# Audio-Hate-Speech-Classification

With the rise in online communication within the Bengali community, hate speech has become increasingly prevalent. This project addresses the lack of Bengali audio resources by creating a hate speech dataset from platforms like YouTube, focusing on binary classification. We analyze key audio features using various models, including SVM, KNN, LR, RF, and CNN, highlighting the need for robust datasets in hate speech detection across different modalities.

The current audio dataset is imbalanced, but it will be updated in the future to achieve more accurate results.

Steps that were followed here:
Audio Hate Speech Classification:

1. Extraction of audio files from YouTube using pytube
2. Segmentation of the audio files
3. Extracting audio features such as mfcc,spectral rolloff, chroma, spectral bandwidth,spectral centroid, spectral contrast
4. Using these features for binary classification of audio using KNN,SVM,RF,LR,CNN

Transcribed Hate Speech Classification:

1. Preprocessing bengali data
2. Showing the GRU model to classify the hate speech into multilabel such as Religious hate speech, Political Hate speech, Personal Hate Speech and Neutral Speech

The repository is in the process of being updated to enhance the performance. And the paper of this project is currently under review process.

All rights reserved by Maayeesha Farzana.
