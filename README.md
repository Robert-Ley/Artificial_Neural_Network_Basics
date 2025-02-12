# Artificial_Neural_Network_Basics

A repository of functions and models used to create artificial neural networks in Python and/or TensorFlow.

## Please Note: 

Scripts containing TensorFlow were written in v1 and contain functions now deprecated if running v2.  I intend to migrate them all over to v2 when I have time but in the meantime if you want to run any of these scripts with TensorFlow2 you should be able to do so by starting with:

```
import tensorflow.compat.v1 as tf

tf.disable_v2_behavior()
```

and removing 


```
import tensorflow as tf
```

# Files

## Art_Creation_with_Neural_Style_Transfer.ipynb

Neural Style Transfer model written in TensorFlow.  To run this you will need the imagenet-vgg-verydeep-19.mat file which is unfortunately too large to upload to GitHub but can be found on Kaggle. You will also need starry.jpg and stpauls.jpg if you wish to run it on the same images used in the notebook.

## Hello_World_of_Deep_Learning.ipynb

A single neuron single layer network tasked to solve a simple problem in Keras.  Taken from deeplearning.ai.

## NLP_Sarcasm_Classifier.ipynb

A simple NLP model that classifies text as either being sarcastic or not.  To run this the sarcasm.json data file needs to be placed in the same folder as the notebook.

## Optimization_Methods_in_Python.ipynb

Gradient descent, mini-batch gradient descent, momentum and Adam optimizers written from scratch in Python i.e. no TensorFlow or Keras; includes mathematical equations in LaTeX. 

## Residual_Network_ResNet-50_in_Keras

A 50-layer residual network for translating images of sign language.  Written in Keras.

## Simple_Convolutional_Neural_Network_in_Keras.ipynb

A simple convolutional neural network written in Keras.  To run this you will also need the test_happy.h5 and train_happy.h5 files.

## Simple_Convolutional_Neural_Network_in_Keras_(ImageDataGenerator).ipynb

An even simpler ConvNet making use of ImageDataGenerator and the Keras Sequential API.

## Simple_Convolutional_Neural_Network_in_Keras_(ImageDataGenerator_and_Transfer_Learning).ipynb

As above but also uses transfer learning by training own fully connnected layers attached to the convolutional layers with pre-trained (and frozen) weights from the Inception model.

## Simple_Convolutional_Neural_Network_in_Python.ipynb

A simple convolutional neural network written from scratch in Python i.e. no TensorFlow or Keras; includes mathematical equations in LaTeX. 

## Simple_Convolutional_Neural_Network_in_TensorFlow.ipynb

A simple convolutional neural network for translating images of sign language.  Written in TensorFlow.  To run this you will also need the test_signs.h5 and train_signs.h5 files.

## Simple_L-Layer_Neural_Network_in_Python.ipynb

A simple L-layer neural network written from scratch in Python i.e. no TensorFlow or Keras; includes mathematical equations in LaTeX.  For some reason GitHub will not render the LaTeX code in the Cost Function markdown cell; it does, however, render just fine in Jupyter Notebook.

## Simple_Neural_Network_in_TensorFlow.ipynb

A simple neural network for translating images of sign language.  Written in TensorFlow.  To run this you will also need the test_signs.h5 and train_signs.h5 files.

## TensorFlow_Basics.ipynb

Runs through the basics of TensorFlow using loss, cost, linear, sigmoid and one-hot encoding functions as examples.

## sarcasm.json

Data for NLP_Sarcasm_Classifier.ipynb.

## starry.jpg

For use with Art_Creation_with_Neural_Style_Transfer.ipynb.

## stpauls.jpg

For use with Art_Creation_with_Neural_Style_Transfer.ipynb.

## test_happy.h5

Test data for Simple_Convolutional_Neural_Network_in_Keras.ipynb.

## train_happy.h5

Training data for Simple_Convolutional_Neural_Network_in_Keras.ipynb.

## test_signs.h5

Test data for Residual_Network_ResNet-50_in_Keras, Simple_Neural_Network_in_TensorFlow.ipynb and Simple_Convolutional_Neural_Network_in_TensorFlow.ipynb.

## train_signs.h5

Training data for Residual_Network_ResNet-50_in_Keras, Simple_Neural_Network_in_TensorFlow.ipynb and Simple_Convolutional_Neural_Network_in_TensorFlow.ipynb.
