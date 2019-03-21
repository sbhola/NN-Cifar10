# Classifying Cifar10 dataset using CNN and Residual Networks
This project is for the EECS 435 Deep Learning at Northwestern University, McCormick School of Engineering. This work is done by the following team members:
1. ##### Siddharth Bhola #####
2. ##### Rekha Goverthanam #####
3. ##### Kailasharam Umayaorupagam #####

We provide a comprehensive study of the [Cifar10 dataset ](https://www.cs.toronto.edu/~kriz/cifar.html), preprocess the dataset by normalization and one-hot encoding, develop a 14 layer Convolution Neural Network using Tenforflow, and dive deep into [Residual Networks](https://arxiv.org/pdf/1512.03385.pdf) and develop a 20 layer Residual Network using Keras:
1.  ##### Cifar10_CNN_01.ipynb has introduction to Cifar10 and CNN implementation. 

2.  ##### Cifar10_ResNet_02.ipynb presents a brief study on Residual Networks and 20 layer implementation. #####


| Architecture               | Epoch # | Test Accuracy |
|----------------------------|---------|---------------|
| Convolution Neural Network | 10      | 73.23%        |
| Convolution Neural Network | 50      | 78.01%        |
| Residual Network           | 10      | 74.5%         |
| Residual Network           | 50      | 85.32%        |