---
title: About
permalink: /about/
classes: wide
---

# About Me
Welcome to the world of Aaron! I'm an undergraduate student at UCLA studying computer science. I'm passionate about all things machine learning and data science. Basketball, football and fishing aren't too bad either. 

## Activities
<img src="../images/ACM-AI.png" style="height: 2em"> **ACM AI**

I'm currently an officer with [ACM AI at UCLA](https://github.com/uclaacmai), a club that strives to educate students on machine learning through workshops. This spring I will be working with four other officers to develop and teach a beginner ML course that will teach linear regression, logistic regression and neural networks.
<br><br>

<img src="../images/UAS.png" style="height: 1em"> **Unmanned Aerial Systems**

I'm part of a team at UCLA designing and building a drone that will compete in [AUVSI SUAS](http://www.auvsi-suas.org/), a competion where autonomous aerial vehichles perform various tasks like detection, classification and object avoidance.

I'm working on the the vision team. We are using Tensorflow and Keras to build a series of CNNs and FCNs to perform classification and segmentation on shapes and letters. With these models we will construct a vision pipeline that we can use to process images taken by our drone.

## Projects

Feel free to check out more in-depth descriptions of my projects [here](/projects).

### Semantic Segmentation of Faces

I find a lot of enjoyment in using photoshop to put my friend's faces on other people. I decided that rather than going through the hassel of manually cropping out someone's face, I would instead use what I had learned about deep learning to make that task eaiser.

Using Keras and Tensorflow, I was able to train a fully convolutional network to segment faces. After about 10 hours of training on an NVIDIA GeForce GTX 1050 over 9 epochs, the model got to about 94% accuracy. Now, I am using this model to create a website that will allow anyone to quickly and easily extract a face from an image.