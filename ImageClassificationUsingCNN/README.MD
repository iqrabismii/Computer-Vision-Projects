 # :dress: :necktie: :shirt: Image Classification using Convolutional Neural Network(CNN) 
 

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

Classifying images of fashion clothes is an important task in the fashion industry as it helps to categorize and organize clothing items, making it easier for consumers to find and purchase the items they are interested in. This task is also crucial for online fashion retailers, as it enables them to improve their search and recommendation systems, leading to a better customer experience and increased sales. The ability to accurately classify fashion clothes images can also help fashion companies to keep track of their inventory and track trends in consumer preferences. The use of machine learning and computer vision techniques in fashion image
classification can lead to improved accuracy and efficiency, making it an important area of research and development.

## Challenges

There are several challenges in fashion clothes __image classification__, including:

Large variability in clothing styles and designs: Fashion clothing can vary widely in terms of style, color, and pattern, making it difficult to develop a classification model that can accurately categorize all types of clothing.

Image variability: Images of fashion clothing can vary in terms of lighting, background, and angle, making it difficult for the model to focus on the clothing item and accurately classify it.

Occlusion: Clothing items can often be partially occluded by other objects, such as bags, jewelry, or body parts, which can make it difficult for the model to accurately identify the clothing item.

Limited annotated data: The availability of annotated data for fashion clothing images is limited, making it difficult to train accurate models for this task.

Overfitting: Due to the large variability in fashion clothing styles and images, models may have a tendency to overfit to the training data, reducing their generalization performance on unseen data.

Despite these challenges, fashion clothes image classification is an important task that can have a significant impact on the fashion industry. Addressing these challenges through careful data selection, data augmentation, and model selection can lead to improved performance and a more accurate classification of fashion clothing images.

## Deep Learning: Convolutional Neural Network(CNN) 
__Convolutional Neural Networks__ (CNNs) can help in the classification of fashion clothes images by leveraging the power of deep learning to automatically extract features from the images and make predictions.

A CNN consists of multiple layers, including convolutional layers, activation layers, pooling layers, and fully connected layers. The convolutional layers apply filters to the input image, and the activation layers introduce non-linearity into the network. The pooling layers perform down-sampling, reducing the spatial resolution of the feature maps and making the network more robust to small translations in the input image. The fully connected layers combine the features extracted by the previous layers and make a final prediction.

During training, the parameters of the filters and activation functions are learned from the annotated training data, allowing the network to automatically discover the features that are important for the classification task. The trained CNN can then be used to make predictions on new, unseen images.

In conclusion, CNNs are a powerful deep learning technique that can be used for image classification tasks such as fashion clothes classification. They are capable of automatically extracting features from the images, handling variability in the input data, and making accurate predictions.


## EDA
The dataset was taken from __keras__ fashion clothes, which consists of 10 different types of clothes such as t-shirt, dress,jeans etc. The dataset had
70000 images and the data was labelled. 
EDA was done by leveraging the python __skimage__ library. Additionally, the label was one hot encoded by converting them in binary form. 

## Modelling

Five hidden layers were implemented in the model using densely connected network with 32, 64,128,128 and 10 units respectively. Relu was used as activation
function and lastly for output softmax was used at it a multiclass model.  Also, regularisation was also peformed to avoid overfitting of the model. 
Lastly, the predicted was mapped to their respective images by using np.argmax() function. More details are available [here.](https://github.com/iqrabismii/Computer-Vision-Projects/blob/main/ImageClassificationUsingCNN/ImageDetectionUsingCNN%20(1).ipynb)

















