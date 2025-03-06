﻿# HelmetDetection
 ABSTRACT:
 ->Nowadays, road accidents are one of the major causes that leads to human death.
 Among them,motor bike accidents are common and causes critical injuries.
 ->Helmet is one of the main protection unit for a motor bicyclist. However, many fail to
 conform to the law of wearing helmet.
 ->Here, to detect the motorcyclists who are violating the helmet laws, a system using
 image processing and convolutional neural network is implemented.
 ->Once the motorbike is detected, by means of convolutional neural network, it is
 determined whether the motorcyclist is wearing a helmet or not
 TECHNOLOGIES USED:
 ->DeepLearning Models:YOLO (You Only Look Once),CNN
 ->OCRLibraries:Tesseract OCR,EasyOCR
 ->Programming Languages: Python (OpenCV,TensorFlow,Keras
 -> Hardware Requirements: CCTV Cameras,High-performance GPU
 SYSTEM WORKFLOW:
 Image/Video Input: Capturing vehicle images using CCTV or traffic cameras.
 -> Preprocessing: Enhancing image quality, removing noise, converting to grayscale if
 needed.
 -> Selection: Identifying the portion of the image containing the number plate.
 -> Number Plate Detection: Using deep learning models like YOLO or OpenCV-based
 contour detection.
 -> Character Segmentation: Extracting individual characters from the detected plate.
 -> Data Storage & Retrieval: Logging extracted data for future analysis and law
 enforcement actions.
 -> Real-time Monitoring & Alerts: Sending alerts to authorities for unregistered or
 flagged vehicles
