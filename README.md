# Neural-Style-Transfer-2-
Neural Style Transfer deals with two sets of images: Content image and Style image.  This technique helps to recreate the content image in the style of the reference image. It uses Neural Networks to apply the artistic style from one image to another.

### How does Style Transfer work?
The aim of Neural Style Transfer is to give the deep Learning framework the ability to distinguish between the style representations and content image.
NST employs a pre-trained Convolutional Neural Network with added loss functions to transfer style from one image to another and synthesize a newly generated image with the features we want to add.

Style transfer works by activating the neurons in a particular way, such that the output image and the content image should match particularly in the content, whereas the style image and the desired output image should match in texture, and capture the same style characteristics in the activation maps.

These two objectives are combined in a single loss formula, where we can control how much we care about style reconstruction and content reconstruction.

Here are the required inputs to the model for image style transfer:

*** A Content Image *** – an image to which we want to transfer style to
A Style Image – the style we want to transfer to the content image
An Input Image (generated) – the final blend of content and style image
