# esrgan

Reference Paper : ESRGAN: Enhanced Super-Resolution Generative Adversarial Networks


ESRGAN (Enhanced-SRGAN) is capable of generating realistic textures during single image super-resolution. This paper shows improvement of three key components of SRGAN –
network architecture, adversarial loss and perceptual loss and derive an Enhanced SRGAN
(ESRGAN) to further enhance the visual quality.
This Architecture containing several RDDB blocks without Batch Normalization layers and
improve perceptual quality rather than objective quality, such as PSNR.
In ESRGAN Perceptual Index (PI) is a measure of perceptual quality if Higher PI, lower
perceptual quality But in PSNR Root mean square error is a measure of objective quality.It
means higher RMSE, lower objective quality.
ESRGAN took idea from relativistic GAN.It means it is somewhat similar to RGAN which
is used to let the discriminator to predict relative realness instead of the absolute value.
