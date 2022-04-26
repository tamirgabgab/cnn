# cnn

Image classification based on CNN.


## Dataset
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. <br>
<a> https://www.cs.toronto.edu/~kriz/cifar.html </a>

## Model
CNN with single Convolution block and single linear block

## Train + Test
here are 50k training images and 10k test images. (0.83/0.17 split) <br>

69.33% Accuracy on 10k samples

## Error prediction samples
25 random samples chosen as an example to show how the model misclassifies (results from the best model) <br>
![p1](https://user-images.githubusercontent.com/80973047/165308696-cb5862f7-f3a9-4658-a205-a97777c890f5.png)

## Files
### cnn_model.ipynb
running notebook of the code of the train and test

## Dependencies
Python 3.8 <br>
Pytorch <br>
Numpy


