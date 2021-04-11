# cifar10
CIFAR10 dataset in numpy format
Main Cifar10 can be found in https://www.cs.toronto.edu/~kriz/cifar.html
and cite this 
https://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf
To make it easier to use, I convert it to numpy array and only you need to load it 
Labels
'airplane'=0,
 'automobile'=1, 
 'bird'=2,
 'cat'=3, 
'deer'=4,
 'dog'=5, 
'frog'=6, 
'horse'=7,
 'ship'=8,
 'truck'=9
Download and extract the Data.
It contains a 2d array numpy first column includes images and second column determines the labels(classes) by integer.
To load data use:


import numpy as np


cifar10= np.load('cifar10_2D_array.npy',allow_pickle=True)


#show image

plt.imshow(cifar10[100,0])  #display a ship

plt.show()
