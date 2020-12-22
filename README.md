# CNN-for-Sign-Language-Classification

In this repository I explore the Sign Language MNIST data set. This dataset consists of a train and test set. The train set is 27,455 (28x28 pixels) grayscale pictures of the alphabet in sign language, the test set consisits of 7,172 grayscale pictures. 

Here, I build two convolutional neural networks with different architectures to correctly classify pictures of the alphabet in sign language. We have 26 different classes since there are 26 different letters in the alphabet.

A convolutional neural network is a specical type of neural network for image classification. Using each image's pixels as the input data, the main difference between convolutional neural networks and tradional ones is the convolution layer. The convolution layer is used for feature dectection epsically in edge detection, such as the outline of a hand in each photo in this dataset. 

Here this CNN is built in python and based on the tensorflow framework using Keras. 

The accuracy of the different models are as follows:
  - Model 1 (named 'model') has a test set accuracy of 0.9885666370391846 %.

  - Model 2 (named 'model2') has a test set accuracy of 0.0.8954266309738159 %.
