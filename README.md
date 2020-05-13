# TF2-GAN
Simple GAN implementations with Tensorflow 2 for Colab

## Description
The GANs are implemented just to get used to TF2. I used some codes from different repos (links are included in the notebooks). The main contribution is that I override keras model's `train_step`  function so that all the models can be trained using `model.fit` method. I think that is the only contribution :)

## List of implementations

* Improved Training of Wasserstein GANs (*wgan-gp*)
* Spectral Normalization for Generative Adversarial Networks (*wgan-sn*)
* Self-Supervised GANs via Auxiliary Rotation Loss (*ssgan*)
* Adversarial Feature Learning (*bigan*)

## TODO list
* U-GAT-IT
