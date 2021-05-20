# SimpleDNCNN
Simplified DNCNN example

# Training Setting
* This model is not using Residual concept.
* Noise level: 25
* num_of_layers: 17
* Image resolution: 128 x 128
* MSE Loss
* Adam optimizer (lr=0.0001, eps=1e-08)
* 50 epochs on training

# Options
* Tensorboard available
* PSNR checking while training  
  
Please check comments.  
No augmentation, DNCNN S, B options.

PyTorch implementation of the TIP2017 paper [*Beyond a Gaussian Denoiser: Residual Learning of Deep CNN for Image Denoising*](http://ieeexplore.ieee.org/document/7839189/).  The author's [MATLAB implementation is here](https://github.com/cszn/DnCNN).
