# Crack detction dataset and network 


## 1. Dataset
  Pellet crack dataset consists of 640 pellet images with the size of 512×512, in which 320 images are used for model training and the other 320 images are used for model testing.

<img src="https://github.com/zhoushuyi/pellet_crack_detection/blob/master/train/Image_512/IMG1194.png" width="200" height="200">//
pellet image
<img src="https://github.com/zhoushuyi/pellet_crack_detection/blob/master/train/mask_w_512/IMG1194.png" width="200" height="200">//
pellet crack 



## 2. Pellet crack detection network PCDNet

  Architecture of the proposed pellet crack detection network PCDNet. VGG16-based backbone is adopted to obtain different scale features. Extracted features are fed to Res-CBAM for preliminary refinement, and then they are sent to the proposed gated refinement module (GRM) consisting of dilated convolutions and attention gated blocks for the secondary crack refinement. In the decoder part, cross fusion module (CFM) is proposed to integrate multiscale features in a progressive way. Finally, the feature map is fed to two convolution layers and a sigmoid activation function for the final prediction of pellet crack. 

The network will be public after soon.
