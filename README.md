# Two-Class Image Classification using TensorFlow Keras 


This Jupyter based Python script is a personal attempt at understanding and working with an Image Classifying Convolutional Neural Network.
The dataset used for this script is the classic Kaggle Cats vs Dogs dataset. The objective of this script is to build a basic CNN model that can identify and distinguish between pictures of cats and dogs with maximum accuracy.

The script makes use of TensorFlow Keras 2.4.0 to first use a straightforward Sequential Model and then a VGG16 Model.
Although the VGG16 Convolutional Neural Network is a bit of an overkill for a simple objective of two-class classification, we find that the accuracy of the VGG16 Model is significantly higher than that of the Sequential Model.
