
# **Real Time Face Mask Detection**

![Real Time Video](https://github.com/MarwanMohamed95/Face_Mask_Detector/blob/main/Real%20Time%20Video.gif)

### This project is divided into two Notebooks:

- The First Notebook we will implement an algorithm to detect whether a person wears a mask or not by detecting its face first using Haar Cascade pre-trained algorithms then by using MobileNetV2 Architecture (pre-trained Convolutional Neural Network) we applied transfer learning by replacing its last layer with a few Fully Connected Layers which we have trained and the last layer with 2 neurons to predict wearing the mask.

- The Second Notebook we will use the model which we have trained in the first Notebook to predict whether the person wearing a mask or not on real time images and videos.


## Steps of training the model (1st Notebook):

    1. Importing the required Libraries
    2. Preparing the images
    3. Initializing the image generator for data augmentation
    4. Splitting the data into train and test
    5. Constructing the model using Transfer Learning by importing the weights of MobileNetV2
    6. Training the model
    7. Predicting and Evaluating the model
    8. Face Detection phase using HaarCascade algorithm to test the model on input image
    9. Testing the model on an input image

## Steps of real time detection (2nd Notebook):
    1. Importing the required libraries
    2. Loading the Model
    3. Haar Cascade Classifier (Face Detection)
    4. Testing the model on real time images and videos
        4.1. The First Part of this tutorial is to run the face mask detector on a real time image
        4.2. The Second Part of this tutorial is to run the face mask detector on a live video.


## An Overview about the model we used (MobileNetV2):

MobileNetV2 is a convolutional neural network architecture that seeks to perform well on mobile devices. It is based on an inverted residual structure where the residual connections are between the bottleneck layers.

![model](https://www.researchgate.net/publication/342856036/figure/fig3/AS:911929400885251@1594432320422/The-architecture-of-the-MobileNetv2-network.ppm)

## The Accuracy and Losses Curves:

![Photo](https://github.com/MarwanMohamed95/Face_Mask_Detector/blob/main/plot.png?raw=true)

## Some of Test images Results:

Solarized dark             |  Solarized Ocean
:-------------------------:|:-------------------------:
![](https://github.com/MarwanMohamed95/Face_Mask_Detector/blob/main/test.jfif?raw=true)  |  ![](https://github.com/MarwanMohamed95/Face_Mask_Detector/blob/main/Results/Test1Result.jpg?raw=true)


Solarized dark             |  Solarized Ocean
:-------------------------:|:-------------------------:
![](https://github.com/MarwanMohamed95/Face_Mask_Detector/blob/main/test.jfif?raw=true)  |  ![](https://github.com/MarwanMohamed95/Face_Mask_Detector/blob/main/Results/Test1Result.jpg?raw=true)



## 🛠 Skills
Deep Learning, Computer Vision, Python, tensorFlow, OpenCV...


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marwanabdelsalam95/)

