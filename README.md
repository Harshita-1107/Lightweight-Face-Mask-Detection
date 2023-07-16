# Lightweight-Face-Mask-Detection
###The project aims to detect face masks in images using deep learning models. The main objective is to optimize the deep learning model for lightweight face mask detection.

###The deep learning model is a convolutional neural network (CNN) with four convolutional layers and two fully connected layers. The CNN layers are followed by max pooling layers to downsample the feature maps. The model also includes dropout layers to reduce overfitting. The output layer has three neurons with softmax activation for classifying the images as 'with mask', 'without mask', or 'mask worn incorrectly'.

## The model is compiled with Adam optimizer and categorical cross-entropy loss function. The model is evaluated on test data with accuracy, recall, precision, and AUC as metrics. The model is saved after training.
