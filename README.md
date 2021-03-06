# Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution
This repository is as a research project in the field of super resolution. It uses RDN as the generator and spectral norm is used in discriminator.

# Introduction
### This is a trial for super-resolution
The residual dense network has many advantages for reconstructing SR images, and we use GANs to enhance RDN.
The core idea is from the following two papers:
1. Residual Dense Network for Image Super-Resolution
2. cGANs with projection discriminator
##### Generator: Residual Dense Network
![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/RDN.jpg)
##### Discriminator: cGAN projection
![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/pro.jpg)
# Results
These results is just trained about 200,000 iterations (full: 600,000) with batch size of 16. 

|Raw|Bicubic(x4)|RDN_GAN(x4)|
|-|-|-|
|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/hr_flow.jpg)|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/bic_flow.jpg)|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/sr_flow.jpg)|
|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/hr_butf.jpg)|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/bic_butf.jpg)|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/sr_butf.jpg)|
|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/hr_dog.jpg)|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/bic_dog.jpg)|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/sr_dog.jpg)|
|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/hr_cat.jpg)|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/bic_cat.jpg)|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/sr_cat.jpg)|
|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/hr_wom.jpg)|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/bic_wom.jpg)|![](https://github.com/MingtaoGuo/Residual-Dense-Network-Trained-with-cGAN-for-Super-Resolution/blob/master/IMAGES/sr_wom.jpg)|
# Reference 
[1] Zhang Y, Tian Y, Kong Y, et al. Residual dense network for image super-resolution[C]//The IEEE Conference on Computer Vision and Pattern Recognition (CVPR). 2018.

[2] Miyato T, Koyama M. cGANs with projection discriminator[J]. arXiv preprint arXiv:1802.05637, 2018.


