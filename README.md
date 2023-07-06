# Sketch-to-image-translation-using-cGANs
![Generic badge](https://img.shields.io/badge/Deep_Learning:-green.svg) ![Generic badge](https://img.shields.io/badge/Python-V3:-blue.svg)
![Generic badge](https://img.shields.io/badge/Keras:-green.svg)  ![Generic badge](https://img.shields.io/badge/GANs:-blue.svg)    ![Generic badge](https://img.shields.io/badge/Image_Processing:-green.svg)  ![Generic badge](https://img.shields.io/badge/Image_to_Image_Translation:-orange.svg)  ![Generic badge](https://img.shields.io/badge/cGAN:-red.svg)

# Introduction
What is Image to Image translation? <br>
 “Image-to-Image Translation” means to transform an image from its original form to some
synthetic forms (style, partial contents, etc.) automatically, while keeping the original structure or
semantics. <br>
Nowadays, Image to Image translation using Deep Learning is a well known method to solve
various problems in Computer Vision like Image Colorization, Semantic segmentation, image
generation for data augmentation, etc. Image-to-image translation problems often referred to as
per-pixel classification or regression.
<br>
In this project, we will be working to solve the problem of Sketch to Photo generation by using
the Deep Learning model called GANs. Generative Adversarial Networks are showing
approximation of Complex data distribution, in the past years. <br>
**Advantages** <br>
● Since, in supervised learning data labeling is an expensive and time consuming task, but,
GANs are able to learn with unlabelled data. <br>
● GANs can generate more realistic samples.

This project can be used to identify criminals through using their sketches, and missing people
(especially children) to get their actual images.<br>

# Objective 
The objective of this project :
1. Perform image translation using Sketch as a condition to generate RGB image.
2. Maximize the chance for recognizing real images as real and generated images as fake
.i.e. The maximum likelihood of the observed data. To measure the loss, we use cross entropy. <br>

# Dataset <br>
In this project we employed CUHK Sketch to Face dataset. From the dataset we made a pair of
90 images for training and 101 for testing as per original sources. <br>
# Result <br>
From the obtained results, it can be concluded that cGAN gives promising results with
accuracy 98%.
![Screenshot 2021-12-15 170051](https://user-images.githubusercontent.com/30427045/163821715-0c8c86b3-89d1-4e03-936b-450059e38a2a.png)
![sdfs](https://user-images.githubusercontent.com/30427045/163821730-2ca10209-7f59-4dbd-a4a5-d2ae1842e4ac.png)
