# OpenImages-ResNet-TransferLearning

This was a homework for the Deep Learning course VITMAV45 of Budapest University of Technology and Economics.  
The task was to download a dataset from Google OpenImages, and perform a binary image classification task on it, using Transfer Learning.  
It had 2 transfer learning tasks:  
In task 1, I had to freeze all layers of the model, except for the last Dense ones, which made the output prediction.  
In task 2, after the learning for task 1 had finished, I had to allow the last convolutional block to be trainable as well, and continue the training.  

I used the <a href="https://arxiv.org/abs/1512.03385">ResNet50</a> model for the task, and the 2 image types were Coffee and Dog.

The code for the data acquisition, preprocessing and model training can be read in the  <a href="https://github.com/darkpanther99/OpenImages-ResNet-TransferLearning/blob/main/Openimages_ResNet_TransferLearning.ipynb">.ipynb file</a> .
