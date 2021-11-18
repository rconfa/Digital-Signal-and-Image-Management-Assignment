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
