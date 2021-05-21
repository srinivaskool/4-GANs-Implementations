# 4-GANs-Implementations

Human Faces
https://colab.research.google.com/drive/18fLFoxI56ETCbLIDJKWTwTdvKfihKVnt?usp=sharing

MNIST
https://colab.research.google.com/drive/1s-Nc5RwPNyd9enJ52TmucFZcuIzads8P?usp=sharing

ART
https://colab.research.google.com/drive/1uUDzAK6St4_AZFu_uBVXQjxefGhNa8f4?usp=sharing

Anime Faces
https://colab.research.google.com/drive/1xFWyerR7-49Z-6lncSLfw_JJU8VUzhh5?usp=sharing


Let's load this dataset using the ImageFolder class from torchvision. We will also resize and crop the images to 64x64 px, and normalize the pixel values with a mean & standard deviation of 0.5 for each channel. This will ensure that pixel values are in the range (-1, 1), which is more convenient for training the discriminator. We will also create a data loader to load the data in batches.




The dataset has a single folder called images which contains all 63,000+ images in JPG format.
