# Sign-Language-Recognition
A deep learning model that recognizes sign language alphabets. 

## Number of Hidden Layers : 4 
A deep neural network is used to gather train on more features. Currently, we have 25 classes, thus a deep NN is needed to distinguish each alphabet from the other and achieve higher accuracy.

Number of training examples = 27455
Number of test examples = 7172

X_train shape: (784, 27455), Y_train shape: (25, 27455), X_test shape: (784, 7172), Y_test shape: (25, 7172)

Number of channels in each image : 1 (Grayscale), Size of each image vector = 28 x 28 x 1 = 784

## Deep Learning Framework : Tensorflow

# Model : Linear -> Relu -> Linear -> Relu -> Linear -> Relu -> Linear -> Softmax 



## Hand Gestures : 
![amer_sign2](https://user-images.githubusercontent.com/53033648/78063390-21d5c800-735e-11ea-86e3-5696da3783e3.png)


Dataset : https://www.kaggle.com/datamunge/sign-language-mnist

## Contributing
Pull requests are welcome. 
