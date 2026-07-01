# Indian Sign Language Translation System

## Project Overview

This project is a real-time Indian Sign Language (ISL) translation system that recognizes hand gestures and converts them into readable text. The system combines **OpenCV**, **MediaPipe**, and **TensorFlow** to perform real-time gesture recognition using a webcam.

MediaPipe extracts hand landmarks from each video frame, and a TensorFlow model classifies the detected gesture into one of the supported Indian Sign Language classes.

---

# Problem Statement

Communication between hearing-impaired individuals and people unfamiliar with sign language can be difficult. This project aims to bridge that gap by automatically recognizing Indian Sign Language gestures and translating them into text in real time.

---

# Features

* Real-time webcam-based gesture recognition
* Hand detection using MediaPipe
* Feature extraction using 21 hand landmarks
* TensorFlow-based gesture classification
* Supports 10 Indian Sign Language gesture classes
* Live prediction display

---

# Project Workflow

1. Capture webcam frames
2. Detect hand using MediaPipe
3. Extract 21 hand landmarks
4. Convert landmarks into feature vectors
5. Predict gesture using TensorFlow model
6. Display predicted gesture

---

# Project Architecture

```text
        Webcam
           │
           ▼
       OpenCV
           │
           ▼
  MediaPipe Hand Detection
           │
           ▼
  Hand Landmark Extraction
           │
           ▼
 TensorFlow Classification Model
           │
           ▼
   Gesture Prediction
           │
           ▼
    Display Result
```

---

# Technologies Used

### Programming Language

* Python

### Libraries

* OpenCV
* MediaPipe
* TensorFlow
* NumPy

---

# Dataset

The project was trained on approximately **1,000 gesture samples** across **10 Indian Sign Language (ISL) gesture classes**.

MediaPipe extracts **21 hand landmarks** from each gesture, which are used as input features for model training.

---

# Data Preprocessing

* Webcam image capture
* Hand detection
* Landmark extraction
* Feature vector generation
* Dataset preparation for model training

---

# Model

A TensorFlow deep learning model was trained to classify hand gestures into 10 ISL classes.

### Model Performance

| Metric           | Result |
| ---------------- | ------ |
| Gesture Classes  | 10     |
| Training Samples | ~1,000 |
| Accuracy         | ~80%   |

---

# Results

* Developed a real-time Indian Sign Language translation system.
* Processed approximately 1,000 gesture samples across 10 ISL gesture classes.
* Extracted 21 hand landmarks using MediaPipe for feature extraction.
* Trained a TensorFlow model with approximately 80% classification accuracy.
* Integrated webcam-based real-time gesture prediction using OpenCV.

