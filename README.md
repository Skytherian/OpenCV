# OpenCV
Separate repo for OpenCV projects 


##[**Detecting number plates of cars**](detectnumberplate.ipynb)
In this project we try to extract the number plate of a car from an image.
The image is first grayed and blurred, and then the Canny method is applied for edge detection using the OTSU threshold.
Afterwards we grab the largest contours which have four sides. That would be the number plate.

##[**DCGAN to Generate CIFAR10 Small Color Photographs using PyTorch**](./GAN/cifar_gan.ipynb)
In this project we have tried to generate images using samples from the CIFAR10 dataset using a DCGAN
