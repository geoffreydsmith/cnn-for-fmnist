# CNN models for FashionMNIST and MNIST
I experimented with various deep learning architectures for classifying small images of fashion items (FashionMNIST) and digits (MNIST) respectively.
The top performance of any model in the notebook was a CNN architecture (model7 in the models notebook), which achieved test accuracy of 91.8 % and 99.2%
on FMNIST and MNIST respectively.

# Contents
The primary work in this folder is the Jupyter notebook models.ipynb, in which I train 8 different models on FMNIST (and 2 on MNIST). 
The best model both in validation and testing was Model 7, and its trained form is present in the compressed folders trained_FMNIST_model.zip and trained_MNIST_model.zip. Both such models can be used for immediate prediction on their respective datasets. Note: both models take as input a 28 x 28 x 1 numpy array of integers 0--255, rather than e.g., a Datasets object or Tensorflow tensor

# Future work
These models are relatively small by deep learning standards. Indeed, the literature is replete with examples of CNN architectures that beat out the
performance of model7 on FMNIST, typically by using larger models. In the future, I will hopefully be able to improve the quality of these models
by adding compute or giving the models more time to train. The most computationally expensive model in this version took 40 minutes to train in
my free Google Colab account; per the literature, more time or compute could substantially improve these models.
