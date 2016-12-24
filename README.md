# MNIST-txt

The [MNIST](http://yann.lecun.com/exdb/mnist/) training and testing datasets as plain UTF-8 text files. 


Formatting 
=========

Each line contains comma separated values representing the image label (0 -9) followed by the pixels grey values (0 - 255).

More precisely, a line contains 1 label value, 784 pixel values, 784 commas and one line break. 

The pixel values are organized in the exact same way as the raw idx files (i.e. row-wise; top to bottom...)



>Label,pixel(1,1),pixel(1,2), . . . ,pixel(24,24)


