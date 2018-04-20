# MNIST-loader

Downloading the [mnist folder](https://github.com/burklight/MNIST-loader/tree/master/mnist) you will be able to have a prepared MNIST dataset ([Le cun et al.](http://yann.lecun.com/exdb/mnist/)) loader for C++.

The folder contains:
- The readMnist.hpp file: The header you will need to include in your c++ code to be able to use the dataset.
- The dataset in the original format provided by Le Cun.

An example on how to use this loader can be found in the [example.cpp](https://github.com/burklight/MNIST-loader/blob/master/example.cpp) file.

** Note the images will be a 3D vector of integers with 0's on the non drawn parts of the image and 1's on the other places.

** Note the labels will be a 1D vector of integers with the label being the number corresponding to de digit.
