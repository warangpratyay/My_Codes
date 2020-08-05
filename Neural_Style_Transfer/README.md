Neural style transfer is an optimization technique used to take two images
—a content image and a style reference image (such as an artwork by a famous painter)—
and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.

This is implemented by optimizing the output image to match the content statistics of the content image and the style statistics of the style reference image. 
These statistics are extracted from the images using a convolutional network.

Here I have used the convolutional layers from 'vgg16' model.
We need two layers- style & content
We use the intermediate layers of the model to get the content and style representations of the image. 
Starting from the network's input layer, the first few layer activations represent low-level features like edges and textures. 
As we step through the network, the final few layers represent higher-level features—object parts like wheels or eyes. 
In this case, we are using the VGG16 network architecture, a pretrained image classification network. 
These intermediate layers are necessary to define the representation of content and style from the images. 
For an input image, we try to match the corresponding style and content target representations at these intermediate layers.
