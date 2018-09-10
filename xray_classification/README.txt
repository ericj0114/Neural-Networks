README

OVERVIEW:
This project takes a set of images and classifies them into 'normal' and 'pneumonia' patients. 
A convolutional neural network was built using the Keras API and TensorFlow as a backend.
Main architecture used pretrained VGG16 model, with custom fully connected layers replacing
default VGG16 connected layers. 

NOTES:
Training image files must be in structure 'data/train/(one folder for each class)'

Validation image files must be in structure 'data/val/(one folder for each class)'

'xray.zip' contains folder 'data', with the subdirectories detailed above.

Required packages:
tensorflow *WARNING* model will run extremely slowly on CPU. Running model on GPU is highly recommmended.
tensorflow-gpu (if using GPU)
numpy
keras
sklearn
matpotlib
