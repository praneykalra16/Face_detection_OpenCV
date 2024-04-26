# Face Detection using OpenCV

This project demonstrates real-time face detection using OpenCV in Python.

## Introduction

This Python script captures video from the webcam and detects faces in real-time using the Haar Cascade classifier provided by OpenCV.

## Installation
1. pip install opencv-python
2. python face_detection.py
3. If you don't have a pre-trained cascade file for face detection on your PC, you can download one from the OpenCV GitHub repository or other reliable sources. OpenCV provides pre-trained cascade classifiers for various tasks, including face, eyes, and pedestrian detection.
You can find the pre-trained cascade classifiers for face detection at the following location on the OpenCV GitHub repository:
[haarcascades](https://github.com/opencv/opencv/tree/master/data/haarcascades)

Within this directory, you'll find the XML files for different cascade classifiers. For face detection, the XML file you're looking for is typically named haarcascade_frontalface_default.xml.

Once you download the XML file, you can specify its path in your Python code where you initialize the CascadeClassifier. 
