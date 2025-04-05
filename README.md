# Neural Style Transfer using TensorFlow

## Overview

This project explores the fascinating realm of Neural Style Transfer, using TensorFlow's pre-trained models from TensorFlow-Hub. The essence lies in merging the content of one image with the artistic style of another, creating visually captivating results through Convolutional Neural Networks.

## Example Scenario

Imagine transforming a photo of your apartment into a masterpiece envisioned by Mozart. By selecting a content image (your apartment) and a style image (a painting by Mozart), you can generate a stylized image that reflects the unique blend of both.

## Evaluation of Style Transfer

To refine the stylized image, we assess three key parameters:

1. **Content Loss:** Measures the difference between the content of the original and generated images.
2. **Style Loss:** Evaluates the variance in artistic style between the chosen style image and the generated image.
3. **Variation Loss (Regularization):** Encourages spatial continuity in the generated image, preventing overly pixelated results.

Utilizing gradient descent, we iteratively minimize these losses, achieving a well-balanced, stylized image. In 20 iterations, we reduce the combined weighted loss value significantly, exemplified by a decrease from "1147329400.0" to "69726370.0." This optimization is critical, ensuring that the output captures the desired content and style in the most effective manner.

## Dependencies

Run this to install the required libraries.
```bash
pip install -r requirements.txt
```

## How to Use

1. **Content Image:** Choose an image that represents the content you want to stylize.
2. **Style Image:** Select an image that embodies the artistic style you desire.
3. **Run the Code:** Execute the provided code, leveraging TensorFlow and its pre-trained models.

## Credits

This project draws inspiration from the groundbreaking paper "A Neural Algorithm of Artistic Style" by Leon Gatys et al. First published on ArXiv in 2015 and subsequently accepted by the peer-reviewed CVPR conference in 2016, this work laid the foundation for neural style transfer.

Feel free to experiment with different content and style images to unleash the artistic potential of your creations!
