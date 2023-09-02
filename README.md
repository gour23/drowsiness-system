# Drowsiness Detection System
## Overview
  This repository contains the code for a drowsiness detection system based on computer vision and deep learning techniques. The system is designed to monitor the eye state of a driver in     real-time and issue an alert when signs of drowsiness are detected.
## Key Features
### Multiple Pretrained Models: 
The system utilizes a range of pretrained models, including DenseNet, InceptionV3, and VGG16, for drowsiness classification.
### Transfer Learning:
 Transfer learning is employed to fine-tune the models for the specific drowsiness detection task.
 ### OpenCV Integration:
 The OpenCV library is used for image processing, face detection, and eye detection.
 ### Sound Alerts:
 When drowsiness is detected, the system triggers a sound alert using the "winsound" library.
 ### Accuracy:
 The model achieves an accuracy of approximately 85%, making it effective in identifying drowsiness-related eye closures.
 ## Prerequisites
 ### Before using this system, ensure you have the following libraries installed:
 OpenCV (cv2)
TensorFlow
Keras
NumPy
winsound

