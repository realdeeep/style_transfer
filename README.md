# style_transfer
Neural style transfer using tensorflow

## What the project is about
Taking the style of one image and content of another image, we get a resultant image. This is done by pretrained model from TensorFlow-Hub which uses Convolutional Neural Networks for this style transfer.

For example, you can take a photo of the apartment you live in, suppose you want to imagine what the apartment whould look like if drawn by Mozart. For this the content image will be your apartment photo and the style image will be a picture of any painting that you deem suitable from Mozart.

## Evaluaiton of style transfer
We take 3 parameters for the evaluation of the model. Content loss, style loss and for regularization, variation loss. We use gradient descent to further reduce the losses and get the optimum stylized image with appropriate amount of content and style. We are able to decrease the combined weighted loss value from "1147329400.0" in the first iteration down to "69726370.0" in the 20th iteration. So, without this gradient descent, we would have ended up with 16.45 times of total the loss value.

## Credits
First published in the paper "A Neural Algorithm of Artistic Style" by Leon Gatys et al., originally released to ArXiv 2015, and subsequently accepted by the peer-reviewed CVPR conference in 2016.
