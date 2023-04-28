 # :point_right: :point_left: :point_up:  Identifying Sign Language using Convolutional Neural Network(CNN) 
 

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org) 
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
[![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/)
[![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org)
[![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) 
[![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org) 
[![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

## Introduction

American Sign Language (ASL) is the primary language used by many deaf individuals in North America, and it is also used by hard-of-hearing and hearing individuals. 
The language is as rich as spoken languages and employs signs made with the hand, along with facial gestures and bodily postures.

## Convolution Neural Networks

CNNs can also be used to recognize sign language, which involves interpreting gestures made with the hands and other parts of the body to convey words and concepts.

Here's how CNNs can help in identifying sign language:

Dataset Preparation: A dataset of images of sign language gestures is needed to train the CNN model. The images can be taken from a camera or recorded videos, where the sign language gestures are captured from different angles.

Data Preprocessing: The images of sign language gestures need to be preprocessed before feeding them into the CNN model. Preprocessing can include resizing the images to a fixed size, normalizing the pixel values, and performing data augmentation techniques such as flipping and rotating the images.

CNN Model Architecture: The CNN model architecture consists of several convolutional layers, followed by pooling layers and fully connected layers. The convolutional layers are responsible for detecting and extracting features from the input images, while the pooling layers reduce the dimensionality of the feature maps. The fully connected layers classify the features into the corresponding sign language gestures.

Training the CNN Model: The CNN model is trained using the dataset of sign language gesture images. The training process involves feeding the input images to the CNN model, computing the loss between the predicted output and the actual output, and adjusting the weights of the model to minimize the loss.

Testing the CNN Model: After training the CNN model, it is tested on a separate dataset of sign language gesture images to evaluate its performance. The performance metrics can include accuracy, precision, recall, and F1 score.

By using CNNs for sign language recognition, we can build models that are able to recognize sign language gestures with high accuracy, which can be used to create applications that aid in communication for deaf and hard-of-hearing individuals. More details are available in this [notebook.](https://github.com/iqrabismii/Computer-Vision-Projects/blob/main/ASL_Recognition/notebook.ipynb)


