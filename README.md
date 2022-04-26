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
16 random samples chosen as an example to show how the model misclassifies <br>
![alt tag](https://github.com/orel1212/MyWorks/blob/main/Deep%20Learning/CaptchaCracking/captcha_errors.JPG)

## Files
### Captcha_Cracking_CRNN_train.ipynb.ipynb
running notebook of the code of the train
### Captcha_Cracking_CRNN_test.ipynb
running notebook of the code of the test
### captcha_dataset.py 
dataset class
### crnn_model.py
crnn class
### utils.py
misc. functions and decoder class

## Dependencies
Python 3.8 <br>
Pytorch <br>
Numpy


