
# Simple GAN using Fully Connected Layers
This repository contains an implementation of a basic Generative Adversarial Network (GAN) using fully connected layers. The code is part of the "Generative Adversarial Networks (GANs)" specialization offered by deeplearning.ai.

## Description
The GAN consists of a discriminator and a generator implemented as subclasses of PyTorch's nn.Module. The discriminator is a fully connected neural network with LeakyReLU activation, while the generator is another fully connected network with LeakyReLU activation and a Tanh activation for output normalization. The GAN is trained on the MNIST dataset using the Adam optimizer and Binary Cross Entropy Loss.
