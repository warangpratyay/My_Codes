This file contains my solution to the Fashion MNIST problem given in Kaggle.

It is similar to simple MNIST but has 10 different classes of images instead of numbers.

Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. 
Each example is a 28x28 grayscale image, associated with a label from 10 classes. 
Zalando intends Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. 
It shares the same image size and structure of training and testing splits.

I have used a simple CNN model with 'checkpoints', 'earlystopping' & 'decaying learning rate' to get a validtion accuracy of 92.13% in just 9 epochs.

Dataset can be downloaded at: https://www.kaggle.com/zalando-research/fashionmnist
