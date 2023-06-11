# Doodle Identification-using-Neural-Network
An artificial neural network (ANN) usually called neural network. It can be considered as a resemblance to a paradigm which is inspired by biological nervous system. In network the signals are transmitted by the means of connections links. The links possess an associated way which is multiplied along with the incoming signal. The output signal is obtained by applying activation to the net input (NN) are one of the most exciting and challenging research areas.

A neural network is made up of vertically stacked components called Layers. Each dotted line in the image represents a layer. There are three types of layers in a NN-
![image](https://github.com/viv3k19/Doodle-Identification-using-Neural-Network/assets/82309435/c424a83e-8063-4b56-9c5b-d42fc1930b34)

In machine learning, backpropagation is a widely used algorithm for training feedforward neural networks. Generalizations of backpropagation exist for other artificial neural networks, and for functions generally. These classes of algorithms are all referred to generically as "backpropagation".

## Features :
* Used 2 different datasets Cifar 10 & Minst. 
* Predefined doddles are trained with the similar kind of patterns. 
* It shows the % rate of doodle/digit it identifies. 
* Model is capable to handle complex patterns.

## Scope :
* Model is limit to only pre-trained doodles & digits. 
* Sometimes backpropagation algorithm fails to identify the patterns.
* Few Dark Cifar 10 dataset images are not recognize by model.

## Model Experiments :
* MNIST Database – Digits
The MNIST database is a large database of handwritten digits that is commonly used for training various image processing systems.
The MNIST database contains 60,000 training images and 10,000 testing images.
![image](https://github.com/viv3k19/Doodle-Identification-using-Neural-Network/assets/82309435/0d319e59-4261-45b3-86dc-3cf8f704c194)
* Doodles!
Doodles are simple drawings that can have concrete representational meaning or may just be composed of random and abstract lines or shapes, generally without ever lifting the drawing device from the paper, in which case it is usually called a scribble.
![image](https://github.com/viv3k19/Doodle-Identification-using-Neural-Network/assets/82309435/caaec6d3-d1e7-41c1-bdb9-5f198a955a59)
* Cifar-10 Dataset
The CIFAR-10 dataset consists of 60000 32x32 color images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

![image](https://github.com/viv3k19/Doodle-Identification-using-Neural-Network/assets/82309435/b9929adc-e17a-40fa-9483-202f3fe639ad)

## Test Results
![image](https://github.com/viv3k19/Doodle-Identification-using-Neural-Network/assets/82309435/c43f340d-fdcc-4fbd-8e95-7f2dbfa6b18b)

## Conclusion :
The model came to an end with a great accuracy and it can honestly defines the patterns which we can train by the lower learn rate as nearest to 0.
But if we slowly move upwards to the learn rate 1 it shows the drastic change on the graph.(it declines because it skips the must include grayscale points).
As we seen in a gradient decent example when the learn rate is slow it slopes down perfectly but if we increase the learn rate it goes randomly to any of the point.
We presented a model that identifies complex patterns (Doodles, Digits, Images) using the Activation, Cost, Derivatives & Backpropation Algorithms. 
With the proper use of datasets our model trained to improve the identification of various recognizable doodles, digits & pictures.

# Project Development Criteria
## Technologies used
* Unity Game Engine
* C#

# Project Creator
* Vivek Malam - Feel free to contact me at viv3k.19@gmail.com for any questions or feedback.









