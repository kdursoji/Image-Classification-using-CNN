# Image-Classification-using-CNN

## How Convolutional Neural Network(CNN) works?
A convolutional network receives a normal color image as a rectangular box whose width and height are measured by the number of pixels along those dimensions, and whose depth is three layers deep, one for each letter in RGB. Those depth layers are referred to as **channels**. For simplification needs we will only consider gray scale image here.

As images move through a convolutional network, different patterns are recognised just like a normal neural network. But here rather than focussing on one pixel at a time, a convolutional net takes in square patches of pixels and passes them through a **filter**. That filter is also a square matrix smaller than the image itself, and equal in size to the patch. It is also called a **kernel**.

<p align="center"><img src="https://ahmedbesbes.com/images/GIF.gif" alt="CNN"></p>

## CNN Model

![image](https://user-images.githubusercontent.com/36665975/71476129-905c3480-2809-11ea-905a-d076ac84fbbe.png)

* **Input Layer:** It represent input image data. It will reshape image into single diminsion array. Example your image is 64x64 = 4096, it will convert to (4096,1) array.
* **Conv Layer:** This layer will extract features from image.
* **Pooling Layer:** This layer reduce the spatial volume of input image after convolution.
* **Fully Connected Layer:** It connect the network from a layer to another layer
* **Output Layer:** It is the predicted values layer.
