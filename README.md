# Convolutional Neural Network (CNN):
A convolutional neural network (CNN) is a type of artificial neural network used in image recognition and processing that is specifically designed to process pixel data.

## Step -1 : Convolution :
## Step -2 : Max pooling
## Step -3 : Flattening
## Step -4 : Full Connection

### from keras.models import Sequential :
To inisialize our Neural Network
### Convolution 2D:
- use it for the frist layer,2D use it for images and 3D use it for Videos
### MaxPooling 2D:
- that make out pooling layer, normally we use 2*2 matrix because we don't want to lose any data.
### Flatten :
- convert all the pool feature map into the large feature vector that will be our fully connected layed
### Dense :
- Add the fully connected layers in a classic ANN
