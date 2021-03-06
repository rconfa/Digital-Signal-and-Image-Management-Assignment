<p float="left">

 <img src="https://github.com/rconfa/Digital-Signal-and-Image-Management/blob/main/images/DSLogo.png" width = "500"/>
 <img src="https://github.com/rconfa/Digital-Signal-and-Image-Management/blob/main/images/BicoccaLogo.png" width = "100" align="right"/>
</p>

# Digital-Signal-and-Image-Management
A repository of assignments and project performed during the Advanced Machine Learning course. 

## 1. Audio Classification
[Audio Classification Folder](Assignment1-AudioClassification/)

The assignment consists in the implementation of an SVM that classify one-dimensional audio signals through the Zero-Crossing Rate (ZCR) feature. This feature extract the number of sign changes present in a mono-channel signal. The goal is to predict the number spoken from the audio file and its characteristics.

The provided dataset is made up of 1500 wav files in which three different subjects pronounce the numbers from 0 to 9. Each file contains the pronunciation of a single number, and each subject pronounces each number fifty times.

## 2. Image Compression
[Image Compression Folder](Assignment2-ImageCompression/)

The assignment consists in experiment with the compression of a color image by blurring the channels of the YCbCr representation. In order to understand the possible different types of compression is required to:
1. Show the effect of blurring with a gaussian filter the chroma channels (Cb and Cr). Either individually or together
2. Show the effect of blurring with a gaussian filter the luma channel (y)
3. Show the effect of blurring with a gaussian filter all the channel togheter.

For each step show the impact of blurring with different intensities either on visual image result and image MB size on disk.

## 3. Image Stitching
[Image Stitching Folder](Assignment3-ImageStitching/)

The assignment consists in experiment with image stitching of two images by using SIFT. In order to implement this assignment is not possible to use `createStitcher()` method of openCV library, however it is possible to use pre-made functions for the computation of the Homography and for image warping.

## 4. Classification Neural Network
[Classification Neural Network Folder](Assignment4-ClassificationNN/)

The assignment requires to solve the classification task for both the MNIST and CIFAR10 datasets by implementing a convolutional neural network with the following layers: 
1. Explicit input layer
2. Convolution (2D) with 32 3??3 filters
3.  ReLU
4.  Max pooling (2D) with a 2??2 filter
5. Flattening
6. Fully-connected mapping to 128 dimensions
7. ReLU
8. Fully-connected mapping to the final problem size

## 5. Fine Tuning and Data Augmentation
[Fine Tuning Folder](Assignment5-FineTuning/)

The assignment requires to solve the classification task for the 101-object dataset by implementing a fine tuning of a neural network. In addition the task requires not to use the mobileNet architecture and experiment with some data augmentation layers.



## About me
&#8860; &nbsp; **Riccardo Confalonieri**

- *Enrolled in*: Master degree in Data Science at University of Milano-Bicocca.
- *Previously enrolled in*: BSCS in Information and Communication Technologies at University of Milano-Bicocca.

<p align="center"> 
  <a href="https://www.linkedin.com/in/riccardo-confalonieri-5250b0201/">
    <img alt="Ayush's Linkdein" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
  </a>
</p><br>
