# SimpleDNCNN
2021 multimedia class ConvNet challenge  
딥러닝 코드 골조 배포를 위한 코드로, 성능을 높이기 위한 데이터 증가, 파라미터 조정 등의 설정은 전혀 하지 않았습니다.  
This is the code for publishing the deep learning code frame, and there is no setting at all to increase the training performance.  

# Training Setting
* This model is not using Residual concept.
* Noise level: 25
* num_of_layers: 17
* Image resolution: 128 x 128
* MSE Loss
* Adam optimizer (lr=0.0001, eps=1e-08)
* 30 epochs on training

# Options
* Tensorboard available
* PSNR checking while training  
  
Please check comments.  
No augmentation, DNCNN S, B options.

PSNR on test dataset: 22.11 (30 epochs)

PyTorch implementation of the TIP2017 paper [*Beyond a Gaussian Denoiser: Residual Learning of Deep CNN for Image Denoising*](http://ieeexplore.ieee.org/document/7839189/).  The author's [MATLAB implementation is here](https://github.com/cszn/DnCNN).
