---
layout: default2
---
[Home](./)


# One-net: Convolutional color constancy simplified




In this paper I tackled the simplest form of computational color constancy where the image is illuminated by only one light source. 
The basic idea behind the method is that since existing methods already achieve results that are indistinguishable to the human eye, lets try creating a neural network that achieves the same results but uses significantly less computational power. For this I created a new CNN model with a novel architecture. This lightweight model contains only 5 convolutional layers achieves state-of-the-art results on several widely used color constancy dataset.
* * *


## Paper abstract

Images have an ever-increasing presence in our daily lives. This increases the need for accurate and efficient image processing. One of the first processing steps in modern cameras is image white-balancing, the process of making the image invariant to the illumination of the scene. This can be achieved by estimating the illumination of the scene, which is used to chromatically adapt the image. Many existing state-of-the-art approaches use pre-trained models as feature extractors. These models are pre-trained on ImageNet and usually have several million parameters. In this paper, we introduce a simple convolutional neural network without pre-trained layers, that achieves state-of-the-art results. The model contains five convolutional layers, and all of them have a small kernel of size (1,1). Experiments with different model complexities and different kernel sizes have shown that high-level semantic information obtained using larger kernels is not required to achieve state-of-the-art results. Cross camera experiments were also performed and they showed that simple image pre-processing can significantly decrease the effect of camera-sensor on the method. The proposed method has less than 22 000 parameters and achieves state-of-the-art results. The model was tested on three different datasets: the Cube+ dataset, the NUS-8 dataset, and the Intel-TAU dataset.

* * *


![image](./assets/imgs/one_net.png)


* * *


### Link to paper [https://doi.org/10.1016/j.patrec.2022.04.035](https://doi.org/10.1016/j.patrec.2022.04.035)



