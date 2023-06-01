# Using GAN for Bob Ross painting generator

GAN (Generative Adversarial Network) is a type of deep learning model consisting of two components: a generator and a discriminator. The generator learns to generate new data instances, such as images, by capturing the underlying patterns and distribution of a training dataset. The discriminator, on the other hand, learns to distinguish between real data instances and the generated ones. Both the generator and discriminator are trained simultaneously in a competitive manner, where the generator tries to fool the discriminator and the discriminator tries to correctly classify the real and generated data. This adversarial training process helps the generator improve its ability to generate realistic and high-quality data samples.

Image-to-image translation using GANs refers to the task of converting an input image from one domain to another, while preserving the underlying structure and content of the image. GANs are employed to learn the mapping between the input and output domains, allowing for the generation of visually plausible images in the target domain. The generator in the GAN model learns to translate the input image into the desired output domain, while the discriminator provides feedback to guide the generator's training. This approach has been successfully applied to various tasks, such as style transfer, colorization, and image super-resolution, enabling the transformation of images from one domain to another with impressive results.


dataset: [Bob Ross Paintings segmented](https://www.kaggle.com/datasets/residentmario/segmented-bob-ross-images), refering: [pix2pix image to image translation](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/generative/pix2pix.ipynb) 
<!-- 
## using eye detection

<p align="center">
<img src="images_outputs/Screenshot 2023-05-21 at 11.56.28 PM.png "Title"using eye detection"/>
</p> -->
