---
layout: default
---
[Home](./)


# Convolutional Neural Networks For Illumination Estimation In Complex Illumination Environments

## Thesis summaray

The Human Visual System is an interesting part of the human body that allows us to perceive the world around us. One of its most fascinating parts is its adaptability. The color of illumination has a significant effect on the color of an object illuminated by said illumination, but we will perceive the color of the object as relatively constant. This is called color constancy.
Unlike humans, cameras cannot automatically remove illumination color from an object. This creates a need to develop a method that emulates the adaptability of the Human Visual System. 

*** 

Many different methods have been developed ranging from simple methods that use image statistics to complex learning-based methods. For the proper training of learning-based methods, a large number of samples is needed. This presents a problem because the creation of quality images with multiple illuminants is a very laborious process so there are not many multi-illuminant datasets. My thesis explores both the development of methods for illumination estimation as well as methods for the creation, labeling, and validation of images with multiple illuminants.

***

Several different methods have been developed for illumination estimation.
The proposed single-illuminant method is a lightweight convolutional neural network that achieves state-of-the-art results on several existing datasets. 

***

The multi-illuminant methods were created for three different situations, for multi-illuminant estimation when the number of illuminants is known apriori, for illumination estimation is performed on a patch-by-patch basis, and illumination estimation for each pixel separately. In addition to estimation methods, two dataset creation methods were developed. The performed experiments show that all proposed methods achieve comparable or better results than methods from the literature.



