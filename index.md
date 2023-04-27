---
layout: default
---

# Hello, I am Ilija Domislović
I am a student at the University of Zagreb Faculty of Electrical Engineering and Computing currently pursuing my Ph.D. in Computer Science.
Am currently at the final stage with my defense hopefully being in June of 2023.

The main focus of my doctoral research is computer vision and machine learning, more specifically color constancy. 
Generally, the area of machine learning interests me and I want to expand my knowledge and continue exploring the capabilities of machine learning.

I created this site[^1] to give a more detailed description of the research I have done for my doctoral thesis.

* * *


## My thesis summary

The Human Visual System is an interesting part of the human body that allows us to perceive the world around us. One of its most fascinating parts is its adaptability. The color of illumination has a significant effect on the color of an object illuminated by said illumination, but we will perceive the color of the object as relatively constant. This is called color constancy.
Unlike humans, cameras cannot automatically remove illumination color from an object. This creates a need to develop a method that emulates the adaptability of the Human Visual System. 

Many different methods have been developed ranging from simple methods that use image statistics to complex learning-based methods. For the proper training of learning-based methods, a large number of samples is needed. This presents a problem because the creation of quality images with multiple illuminants is a very laborious process so there are not many multi-illuminant datasets. My thesis explores both the development of methods for illumination estimation as well as methods for the creation, labeling, and validation of images with multiple illuminants.

Several different methods have been developed for illumination estimation.
The proposed single-illuminant method is a lightweight convolutional neural network that achieves state-of-the-art results on several existing datasets. 

The multi-illuminant methods were created for three different situations, for multi-illuminant estimation when the number of illuminants is known apriori, for illumination estimation is performed on a patch-by-patch basis, and illumination estimation for each pixel separately. In addition to estimation methods, two dataset creation methods were developed. The performed experiments show that all proposed methods achieve comparable or better results than methods from the literature.




* * *


## Research

Here are the 5 papers I have published in pursuit of my doctorate.
You can click on the links to get a detailed description of the research.

* [One-net: Convolutional color constancy simplified](./one_net.html)
* [Outdoor daytime multi-illuminant color constancy](./ispa.html)
* [Shadows & Lumination: Two-illuminant multiple cameras color constancy dataset](./shal.html)
* [Filters & Lumination: Creating multi-illuminant images for computational color constancy](./filters.html)
* [Color constancy for non-uniform illumination estimation with variable number of illuminants](./zane.html)



* * *

## Embedded programming


In addition to computer vision, I Have an interest in the field of embedded programming where I have done several projects.

* The creation of a smart plug that tracks user energy consumption and stores the data on a local server
* The development of a device used in fuel trucks to monitor whether the fuel latch is open. This included the development of the embedded hardware, embedded software, and component testing.
* The creation of a functional camera system on an FPGA board. This included the creation of a driver form camera sensor and FPGA communication, RAW to JPEG decoding, and image storing.



[^1]: Website inspiration from my friend Jeronim. [Github link](https://github.com/jere357)


