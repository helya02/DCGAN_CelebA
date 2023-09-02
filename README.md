# DCGAN_CelebA
DCGAN (Deep Convolutional Generative Adversarial Networks) is a seminal [paper]("https://arxiv.org/abs/1511.06434") in the field of generative modeling, published by Alec Radford, Luke Metz, and Soumith Chintala in 2015. DCGAN introduced a novel architecture for training generative models using adversarial learning, specifically designed for generating realistic images.

The key idea behind DCGAN is to use convolutional neural networks (CNNs) as both the generator and discriminator models in a GAN framework. The generator network takes random noise as input and gradually upsamples it to generate synthetic images. The discriminator network, on the other hand, learns to distinguish between real and generated images.

DCGAN introduced several architectural guidelines that significantly improve the stability and quality of the generated images. Some of these guidelines include the use of convolutional and transpose convolutional layers, avoiding fully connected layers, employing batch normalization, using LeakyReLU activation functions, and implementing proper weight initialization techniques.

The DCGAN paper demonstrated impressive results on various image datasets, including MNIST, CIFAR-10, and LSUN. It showed that DCGANs can generate visually coherent and diverse images that resemble the training data distribution.

Since its introduction, DCGAN has inspired numerous advancements in the field of generative modeling and has become a foundation for many subsequent works, such as Conditional GANs, StyleGAN, and BigGAN. It has played a crucial role in advancing the field of generative models and has opened up new possibilities for image synthesis and generation.


<img width="685" alt="Screen_Shot_2020-07-01_at_11 27 51_PM_IoGbo1i" src="https://github.com/helya02/DCGAN_CelebA/assets/77358433/a3acc9a6-6043-4c0c-8a37-f2cb28af2af3">


