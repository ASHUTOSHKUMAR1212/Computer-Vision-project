# Computer-Vision-project

Face Detection and Recognition System
Project Overview

This project implements a face detection system for Company X's movie streaming app, where users can pause a movie and get details about the actors in the scene.
Domain:

Entertainment
Context:

Company X wants to automate cast information display by detecting faces from movie screenshots. The computer vision team will use this system to identify actors.
Data Description

    Dataset includes images and masks for human faces.

Objective

    Build a Face Detection System.

Steps
Part A

    Data Import and Understanding
        Load and split images into Features (X) and Labels (Y).
        Display a sample image and its mask.

    Model Building
        Use MobileNet and U-Net architecture to detect face masks.
        Train and evaluate the model.

    Testing
        Test model predictions on a sample image.

Part B

    Face Detection
        Detect faces in images using haarcascade_frontalface_default.xml.
        Extract metadata and save it as a .csv.

Part C

    Face Recognition
        Load data and generate face embeddings.
        Use SVM and PCA for classification.
        Test predictions on sample images.

Tools

    Python, TensorFlow/Keras, OpenCV, MobileNet, SVM
