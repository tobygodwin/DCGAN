# DCGAN


This repo implements the Deep Convolutional GAN, as presented by  [Radford et. al](https://arxiv.org/pdf/1511.06434.pdf).

The Jupyter Notebook is based on the submission for a coursework for a course in Deep Learning. It first implements the DCGAN architecture, then trains it on the CIFAR-10 dataset to generate images. A discussion of results is then given. 

## Background

In the case of the DCGAN both the generator and discriminator are deep convolutional networks. The generator upsamples a latent representation z (Gaussian noise) to a volume the same shape as the input iamges. This is done by using transposed convolutions with batch normalisation layers and ReLU activations. Conversely, the discriminator performs a real/fake classification by using strided convolutional layers, batch normalisation and Leaky ReLU activations to downsample the input images, revealing discriminiative features of the input images. 






