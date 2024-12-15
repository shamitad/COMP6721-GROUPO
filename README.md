# COMP6721-GROUPO
1. Beavan Joe Mathias  40274832
2. Harshil Prajapthi  40266103
3. Shamita Datta  40276530
4. Slade Justin Ferrao  40275410


# Classification of Satellite Images and Aerial Data using CNN Models


This project focuses on the critical role of satellite imagery in urban planning, environmental monitoring, and
field surveys. Satellite data, particularly spatial
information, is essential for extracting and analyzing
insights that support informed decisions. To enhance
understanding of image classification, this project
compares the performance of three advanced convolutional
neural network (CNN) architectures: ResNet18,
AlexNet and MobileNetV2 to determine the most
effective model for classifying satellite images accurately
and efficiently.

Data from EuroSAT, RSI-CB, and RESICSC45
are considered to perform satellite image classification.
EuroSAT contains 27,000 labeled satellite images from 10
different land use and land cover categories such as forest,
highway, industrial, residential, and others and can be
downloaded from Kaggle. RESISC45 is a publicly
available benchmark for remote sensing image scene
classification that can be downloaded from TensorFlow. It
contains 31,500 images across 45 classes with 700 images
in each class. RSI-CB is also used for large-scale remote sensing image classification. It contains 7 classes and
around 45 subclasses under each class. For a more diverse
number of classes over the datasets that are being used in
the project, only 5 of the major classes are considered,
making the total dataset to be of 22,000 images over. 



# Links to access the datasets
EuroSat-
https://www.kaggle.com/datasets/apollo2506/eurosat-dataset

RESISC45- 
https://www.tensorflow.org/datasets/catalog/resisc45

RSI-CB-
https://github.com/lehaifeng/RSI-CB

# Instruction on how to train/validate your models
To train and validate the model, there are multiple .ipynb files corresponding to each dataset and each model. The models are saved in the respective folders as per the CNNs. To train the model, datsets can be downloaded from the given links and uploaded on the google drive as we have done for the training. For preprocessing of the EuroSAT dataset there is a separate file that does so. 
Simply change the location of the dataset in the to perform training on your own. Run all the blocks under the training section. The models weigh would be saved in the current directory. 

# Instructions on how to run the pre-trained model on the provided sample test dataset
You can run the pretrained models by running the blocks under test section in the .ipynb files using the trained models that would be saved for each corresponding training. Dataloader should be preloaded with the test dataset. The validation accuracy, precision, recall and f1 score generated.


# Requirements
Python 3.x

Libraries:

1. torch (PyTorch)
2. torchvision
3. matplotlib (for visualization)
4. numpy
5. scikit-learn
6. PIL (for image processing)
7. opencv-python (for data preprocessing)

# Source code package in pytorch
https://github.com/pytorch/pytorch
