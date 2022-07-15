# Using GAN to generate faces

Generative Adversarial Networks (GANs) have been used in many different applications to generate realistic synthetic data. We propose a novel GAN ​​with an autoencoder (GAN-AE) architecture for generating synthetic probes for variable-length, multi-feature sequence datasets. The main difference between GAN and VAE is that GAN tries to fit pixel-level distribution instead of data distribution, it optimizes the model distribution to the true distribution in a different process.

In this project it's used a simple GAN to generate faces using the [CelebA dataset](https://www.kaggle.com/datasets/jessicali9530/celeba-dataset). It's also used a relative small numbers of epochs for academic test reasons.