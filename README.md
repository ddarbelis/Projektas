# UDACITY CAPSTONE Deep learning project
---------------------

## Problem statement
In this capstone project the objective is to develop a deep learning Android app to decode sequences of digits from natural images. For this we use the Street View House numbers (SVHN) dataset, which is a real world collection of images obtained from Google Street View Images, to train deep learning models within the app.
##Application architecture
In this project to recognize numbers, the images app uses detection and classification convolution neural network (CNN) models. 
The app detection and classification pipeline:
1.	Get input image (taken by phone camera)
2.	Resize image to 64x48x3 and then normalize it
3.	Feed processed image into detection CNN to get bounding box coordinates
4.	Calculate bounding box coordinates in original image and display image with bounding box on the app 
5.	Cut the bounding box area and resize to 54x54 
6.	Feed the image to classification CNN to get number of digits and digits predictions 
7.	Display number prediction on app 


