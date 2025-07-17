# ESRGAN

Enhanced Super-Resolution Generative Adversarial Networks.

In few words, image super-resolution (SR) techniques reconstruct a higher-resolution (HR) image or sequence 
from the observed lower-resolution (LR) images, e.g. upscaling of 720p image into 1080p.

One of the common approaches to solving this task is to use deep convolutional neural networks 
capable of recovering HR images from LR ones. And ESRGAN (Enhanced SRGAN) is one of them. Key points of ESRGAN:
1. SRResNet-based architecture with residual-in-residual blocks;
2. Mixture of context, perceptual, and adversarial losses. Context and perceptual losses
are used for proper image upscaling, while adversarial loss pushes neural network to the natural image manifold
using a discriminator network that is trained to differentiate between the super-resolved images and original photo-realistic images.
