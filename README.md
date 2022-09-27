# CNN models for FashionMNIST and MNIST
I experimented with various deep learning architectures for classifying small images of fashion items (FashionMNIST) and digits (MNIST) respectively.
The top performance of any model in the notebook was a CNN architecture (model7 in the models notebook), which achieved test accuracy of 91.8 % and 99.2%
on FMNIST and MNIST respectively.

# Future work
These models are relatively small by deep learning standards. Indeed, the literature if replete with examples of CNN architectures that beat out the
performance of model7 on FMNIST, typically by using larger models. In the future, I will hopefully be able to improve the quality of these models
by adding compute or giving the models more time to train. The most computationally expensive model in this version took 40 minutes to train in
my free Google Colab account; per the literature, more time or compute could substantially improve these models.
