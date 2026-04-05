# 🎙️ Audio Hate Speech Classification for Bengali

<div align="center">

**A Deep Learning System for Detecting and Classifying Hate Speech in Bengali Audio**

![License](https://img.shields.io/badge/License-Rights%20Reserved-red.svg)
![Language](https://img.shields.io/badge/Language-Python%20%7C%20Jupyter-blue)
![Status](https://img.shields.io/badge/Status-Active%20Development-green)
![Topics](https://img.shields.io/badge/Topics-Audio%20%7C%20NLP%20%7C%20ML%20%7C%20DL-orange)

</div>

---

## 📋 Overview
This project was inspired by the widespread rise of hate speech in the Bengali community following a communal conflict in Bangladesh in 2021. It addresses the critical need for Bengali audio hate speech detection by developing a comprehensive system that leverages both audio signal processing and natural language processing techniques. With the increase in online communication within the Bengali community, hate speech has become more prevalent, making automated detection tools essential for content moderation and online safety.

The project implements multiple machine learning and deep learning approaches:
- **Audio-based classification** using MFCC and spectral features with traditional ML algorithms
- **Audio-based classification** using Convolutional Neural Networks (CNN)
- **Text-based classification** using Gated Recurrent Unit (GRU) networks on transcribed speech

---

## 🎯 Key Features

- 🎵 **Audio Extraction** - Extract audio from YouTube videos using pytube
- 🔊 **Audio Segmentation** - Intelligently segment long audio files into manageable chunks
- 📊 **Feature Extraction** - Extract advanced audio features (MFCC, spectral properties, chroma)
- 🤖 **Multiple ML Models** - KNN, SVM, Random Forest, Logistic Regression
- 🧠 **Deep Learning Models** - CNN and GRU architectures
- 🏷️ **Multi-label Classification** - Religious, Political, Personal hate speech + Neutral
- 📝 **Bengali NLP** - Specialized text preprocessing for Bengali language
- 🔄 **End-to-end Pipeline** - From raw audio to classification results

---

## 🏗️ Project Architecture

### Two-Pronged Approach:

**Approach 1: Audio-Based Classification**
- Feature Extraction (MFCC, Spectral, Chroma)
- Machine Learning Models (KNN, SVM, RF, LR)
- CNN Deep Learning Model

**Approach 2: Text-Based Classification**
- Speech-to-Text Transcription
- Bengali Text Preprocessing
- GRU Multi-label Classification