# SKIN CANCER DETECTION USING CONVOLUTION NEURAL NETWORK

## Report Link: 
https://humberital-my.sharepoint.com/:w:/g/personal/n01536755_humber_ca/EZOKoqFiPPdPq3SEUE_CSLsBEKjHWqhqGMnJU91H5uBCvQ?e=b88e6N

## Purpose:
Skin cancer is mostly common nowadays and more surprisingly, people don't come to know because they lack awareness. Melanoma also known as malignant melanoma is the most lethal form of skin cancer and is responsible for more than 70% of skin cancer deaths. The best possible way suggested is to identify it as early as possible and treat it with minor surgery. In this paper, we have proposed a Convolutional Neural Network (CNN)-based approach for the early detection of skin cancer. 

## Dataset: 
ISIC 2020 Challenge Dataset

## Methodology:

### CNN and Batch Normalization:
The methodology employed in this project involves the utilization of a Convolutional Neural Network (CNN) architecture for the task of facial expression recognition. The chosen CNN model is constructed using the Keras library, comprising multiple layers such as convolutional, batch normalization, activation, max-pooling, dropout, and fully connected layers.


## Experiments and Results
### Model 1
The dataset is divided into training and testing datasets. Then when we started our evaluation we took an 80% training set and 20% validation dataset so that we could compare after we trained our model. We use a learning rate of 0.0001, a batch size of 32. 

### Model 2
Implemented data augmentation with drop out layer.We have done randomRotation and randomZoom by 0.2. The model starts with three convolutional blocks. Each block consists of a convolutional layer with a specific number of filters and 3 × 3 kernel size. To improve the training and performance of neural networks and faster convergence we apply batch normalization after each convolutional layer, and the rectified linear unit (ReLU) activation function to introduce non-linearity. This experiment also adopted a categorical cross-entropy loss function

### Model 3
We increased the traning data to include 8992 images and validation to have 2247 images. This was done to balance the data.

![Alt text](/../main//Model%203.png?raw=true "Optional Title")

In conclusion, the challenges that we have proposed like overfitting, computational resources, false positives, and negative class imbalance, we have implemented all of through the CNN model and tried to improve and train our model so that we can get better accuracy as well as model be trained to its best to give accurate results. 
![image](https://github.com/siddhesh-its/SkinCancerDetectionUsingCNN/assets/113104423/e7dd3fe6-43d7-4c26-9786-3f61dea1ed4a)


