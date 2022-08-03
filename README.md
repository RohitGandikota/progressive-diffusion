# Progressively-Growing-Diffusion-Models
Codebase for the BMVC-2022 submission "Pro-DDPM: Progressive Growing of Variable Denoising Diffusion Probabilistic Models for Faster Convergence".
</br>

```
We explore the concept of progressive growth of network layers in denoising diffusion probabilistic models. We describe a new training methodology to train Denoising Diffusion Probabilistic Models (DDPM) for faster convergence speeds. DDPMs have achieved high-quality image synthesis in non-adversarial training; however, their training is computationally intensive due to the Markov chain simulation and sampling for many time steps. The key idea of this work is to progressively increase the network depth of the diffusion model sinusoidally, starting from a low resolution and adding layers as they converge. This showed a 3 times improvement in training speeds while ensuring unprecedented image quality content generation. We compare our model’s training performance with the original DDPM, the improved DDPM, diffusion implicit models, and generative models in terms of FID and log-likelihood. We analyse the image quality and variance of the synthesised images on CelebA-HQ, Animal Faces-HQ, Imagenet and CIFAR-10 datasets. We also describe several implementation details of our training method that are important for quality preservation and faster convergence.
```
