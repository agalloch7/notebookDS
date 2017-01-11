We will look at determining what object is represented in an image. The pixel values will be used as input, and the neural network will then automatically  nd useful combinations of pixels to form higher-level features. 

We will take on the role of a vision system for a car, looking around at any obstacles in the way or on the side of the road. Images are of the following form from the CIFAR 10 dataset:

<p align="center">
    <img src="img/raw_image.png" width="600"/>
</p>

Overall, in this project,

we will examine the following:
• Classifying objects in images
• The different types of deep neural networks
• Theano, Lasagne, and nolearn; libraries to build and train neural networks
• Using a GPU to improve the speed of the algorithms