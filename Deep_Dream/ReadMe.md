DeepDream is an experiment that visualizes the patterns learned by a neural network. 
Similar to when a child watches clouds and tries to interpret random shapes, DeepDream over-interprets and enhances the patterns it sees in an image.

It does so by forwarding an image through the network, then calculating the gradient of the image with respect to the activations of a particular layer. 
The image is then modified to increase these activations, enhancing the patterns seen by the network, and resulting in a dream-like image. 
This process was dubbed "Inceptionism" (a reference to InceptionNet, and the movie Inception).

Here I have used the shapes & patterns learnt by 'inception_v3' model in its various 'mixed' layers.

In deepdream we use gradiant ascent to enhance the patterns seen by the network.
