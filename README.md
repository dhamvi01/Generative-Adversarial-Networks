# Generative-Adversarial-Networks

Generative models are a family of AI architectures whose aim is to create data samples from scratch. They achieve this by capturing the data distributions of the type of things we want to generate.

## The GANs Framework
A GAN is composed of two separate models, represented by neural networks: 
   - Generator G
   - Discriminator D
The goal of the generator is to generate data samples such as to fool the discriminator.

The generator is nothing but a deep neural network. It takes as input a vector of random noise (usually Gaussian or from a Uniform distribution) and outputs a data sample from the distribution we want to capture.

The discriminator is, again, just a neural network. Its goal is, as its name states, to discriminate between real and fake samples. Consequently, its input is a data sample, either coming from the generator of from the actual data distribution.

The output is a simple number, representing the probability that the input was real. A high probability means that the discriminator is confident that the samples he's being fed is a genuine one. On the contrary, a low probability shows high confidence in the fact that the sample is coming from the generator network:

## Type of GAN
  - Wasserstein GANs (WGANs)
  - Self-Attention GANs (SAGANs)
  - BigGANs
  
We will buid the Simple GAN, Let's do it

