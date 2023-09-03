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

## Dataset
### For Downloading the Dataset , visit here :
```http://mrl.cs.vsb.cz/eyedataset```
 
 ## Prerequisites
 ### Before using this system, ensure you have the following libraries installed:
 OpenCV (cv2) <br>
TensorFlow <br>
Keras <br>
NumPy <br>
winsound <br>
### You can install these libraries using pip:
``` pip install opencv-python
    pip install tensorflow
    pip install keras
    pip install numpy
    pip install winsound
```
## Usage
### Clone the repository to your local machine:
``` git clone https://github.com/your-username/drowsiness-detection.git ```
### Navigate to the project directory:
``` cd drowsiness-detection ```
### Run the main script:
```python drowsiness_detection.py ```
<br> This script will start capturing video from your camera and monitor your eye state. If drowsiness is detected, it will trigger an alarm sound.

## Additional Notes
The system supports multiple pretrained models. You can switch between them in the code to experiment with different architectures. <br>
Experiment with different Haar Cascade classifiers for eye detection to optimize the system's accuracy. <br>
Ensure that you have the necessary permissions and consent when deploying this system, especially in scenarios involving privacy and data protection.



