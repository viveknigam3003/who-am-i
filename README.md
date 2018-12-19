# who-am-i

## Introduction
A program that detects the face of a person and identifies them based on the [LBPH](https://towardsdatascience.com/face-recognition-how-lbph-works-90ec258c3d6b) Algorithm. The model is trained over the data set provided by the user using an [IP Webcam]( https://play.google.com/store/apps/details?id=com.pas.webcam&hl=en_IN)© App.

## Working
The `data.py` file is used to gather the dataset of 100 sample images that are clicked using an IP Webcam over the same network. The files are saved in the desired location in grayscale for the LBPH Algorithm to work.<br>Then the `show.py` script is to train the model over the data collected to identify the person who is the `User` in this case. The model will predict the face with a particular accuracy.
