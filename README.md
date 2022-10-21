# Variational_AutoEncoder

A sample VAE model architecture looks:

<img src='imgs/vae_overview.png' width="600" height="400" >

**`VAE_Mnist.ipynb`** shows processes in details that how to build a VAE model and train it on `MNIST` dataset.
When we set the **latent dimension** as `2`, the latent pattern of image categories can be visuailized in 2d plot, together with the reconstructed image, shown as, 
<p float="left">
<img src='imgs/mnist_reconstructed.jpg' width="300" height="300">
<img src='imgs/mnist_reconstructure.jpg' width="600" height="300">
</p>

**`VAE_Anime.ipynb`** is similar as above but trained on dataset of [anime faces dataset by MckInsey666](https://github.com/bchao1/Anime-Face-Dataset). The VAE model will be a little bit of complex than the former (e.g., three conv2d block in encoder). The latent dimension is set as `512`. The reconstructured image is,

<img src='imgs/anime_reconstructed.jpg' width="1000" height="400">

