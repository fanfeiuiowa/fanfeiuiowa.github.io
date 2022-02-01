---
title: "Deep-learning based Prediction Model for Projection Micro-stereolithography (P-µSLA) Process [Click for detail]"
excerpt: "A predicting model for P-µSLA process via convolutional encoder-decoder networks. Related [[Paper]](https://fanfeiuiowa.github.io/files/v01bt02a033-detc2018-85458.pdf)<br/><br/><img src='/images/usla_schematics.png' width='400'/>"

collection: portfolio
---
* **System design of P-µSLA process:** The printer is a bottom-up SLA (DLP) process with a digital projector screen at accuracy of 10 µm. 

<p align="center">
  <img src='/images/usla_schematics.png' width='500'/>
</p>

* **Test cases fabricated by P-µSLA process:** Effel Tower, Batman, Latice Cube and Lattice Sphere were printed.

<p align="center">
  <img src='/images/usla_samples.png' width='600'/>
</p>

* **Convolutional encoder decoder network for result prediction:** Inspired by the success of SegNet for semantic segmentation, the architecture of the proposed deep convolutional encoder-decoder network that consists an encoder network and a decoder network for shape deformation prediction is presented. The encoder network is composed of convolutional layers, batch normalization layers, relu layers, and maxpooling layers. The decoder network contains unpooling layers, transposed convolutional layers, batch normalization layers, relu layers. The end of the network includes a softmax layer and a pixel classification layer that classify the intensity values of each pixel of the predicted image into 0 and 1.

<p align="center">
  <img src='/images/network.PNG' width='700'/>
</p>

* **Comparison with prediction and ground truth of validation patterns:** The actual printed outcomes (groundtruth) and the predicted outcomes (prediction) are all compared correspondingly. By comparing the predicted shapes with the actual printed shapes, it is obvious that the convolutional encoder decoder network is capable to study and simulate the shape deformation caused by the uncertainties within the P-µSLA process. Meanwhile, the randomly sampled points from the boundaries of the two images are overlapped and illustrated in the image below.

<p align="center">
  <img src='/images/comparison.PNG' width='700'/>
</p>