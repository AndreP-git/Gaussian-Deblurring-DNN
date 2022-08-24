# Gaussian-Deblurring-DNN
This project consists of a de-blurring deep learning model, aimed to remove gaussian blur and gaussian noise from images.\n
The goal is to create a model which, taken a blurred image X, is able to reconstruct the original de-blurred image y.
The dataset is built starting from CIFAR-10 images collection, a Gaussian Blur filter is applied to obtain the blurred images used to train the models.
Two architectures are proposed: AutoEncoder vs. ResNet model.
