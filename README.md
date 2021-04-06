## Autoencoders
These are very useful models that consist of an encocder and a decoder block. The main applications of autoencoders are image compression and decompression, image de-noising, etc.

## Table of Contents

1. Linear Autoencoders

## 1. Linear Autoencoders

## Model Architecture

![Screenshot](imgs/architecture.png)<br>

* The basic architecture of a Autoencoder is described by the diagram above. 

* In this notebook we are using the MNIST dataset to compress the 28x28 images and decompress them back to the original image. The architecture of the model used in this project is described below. 

![Screenshot](imgs/Inkedmex_LI.jpg)<br>

## Results

### Note
All these models are trained for 5 epochs. 

* Considering an encoding depth of 32

![Screenshot](imgs/d_32_f.png)<br>

* Considering an encoding depth of 64

![Screenshot](imgs/d_64.png)<br>

* Considering an encoding depth of 128

![Screenshot](imgs/d_128_f.png)<br>

* Considering an encoding depth of 256

![Screenshot](imgs/d_256.png)<br>

## Conclusion

From the above results we can conclude that more the encoding depth better is the resolution of the reconstructed image. But we have to remember that more the encoding depth lesser is the compression. So, while building an autoencoder for image / audio compression we have to choose an optimial encoding depth for best compression and recovery. 

