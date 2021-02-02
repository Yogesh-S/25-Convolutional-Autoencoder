# Convolutional-Autoencoder

In order to get improved performance of autoencoders we can use convolutional layers.

The encoder portion will be made of convolutional and pooling layers and the decoder will be made of **transpose convolutional layers** that learn to "upsample" a compressed representation.

![alt text](https://github.com/Yogesh-S/25-Convolutional-Autoencoder/blob/main/autoencoder_1.png?raw=true)

### Compressed Representation

A compressed representation can be great for saving and sharing any kind of data in a way that is more efficient than storing raw data. In practice, the compressed representation often holds key information about an input image and we can use it for denoising images or oher kinds of reconstruction and transformation!

![alt text](https://github.com/Yogesh-S/25-Convolutional-Autoencoder/blob/main/denoising.png?raw=true)

In this notebook, let us build a convolutional autoencoder (with Transpose Convolutions in the decoder) to compress the MNIST dataset using the architecture shown below.
![alt text](https://github.com/Yogesh-S/25-Convolutional-Autoencoder/blob/main/conv_enc_1.png?raw=true)
