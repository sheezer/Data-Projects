# IBM AI Engineering Professional Certificate
## Introduction to Deep Learning and Neural Networks with Keras

This repository contains the various notebooks completed during the course AI Capstone Project with Deep Learning for IBM's AI Engineering Professional Certificate on Coursera.

### 1-1-Loading-Data

Downloads and visualizes the concrete crack images dataset. This dataset will be later used for training models in the project.

*Tools: Numpy, Matplotlib, PIL(Pillow)*

### 1-2-load_and_display_data

Loads the concrete crack images dataset and visualizes it. The dataset will be used later in the project.

*Tools: Numpy, Matplotlib, PIL(Pillow), Pandas*

### 2-1-Data-Preparation

Uses the Keras library to convert the concrete crack images dataset into batches which may be processed later in the project.

*Tools: Numpy, Matplotlib, Keras*

### 2-2-data-loader


Uses PyTorch to split the concrete crack images dataset into training and validation sets. Afterwards, a Dataset class object is defined for the image dataset to automatically split the data.

*Tools: Numpy, Matplotlib, PyTorch*

### 3-1-Pretrained_Models

Makes use of the pretrained resnet50 model from Keras to train a classifier for the concrete crack images dataset. The input data (concrete crack images) is rescaled for the resnet50 model and the output layer of the resnet50 model is replaced for the available dataset. The model is then trained.

*Tools: Numpy, Matplotlib, Keras*

### 3-2-linearclassifier

Makes use of PyTorch and the Torchvision library. First, creates a Dataset class for the concrete crack images dataset. The dataset is normalized and its values are passed to a custom made Softmax model. The model is trained and its classificaton accuracy recorded.

*Tools: Numpy, Matplotlib, PyTorch, torchvision*

### 4-1-Comparing_Models

Compares the VGG16 and resnet50 pretrained models. First, the VGG16 pretrained model is loaded, the concrete crack images dataset is preprocessed according to its input specifications and the final output layer is modeified according to the current scenario. The model is then trained to classify concrete images as cracked or uncracked. The resnet50 model is loaded from the previous task. The two trained models are then compared for their classification accuracy and the results are recorded.

*Tools: Numpy, Matplotlib, Keras*

### 4-2-resnet18

Makes use of pretrained model resnet18 in PyTorch this time to classify images from the concrete crack images dataset. The custom Dataset class is created to split the data into training and validation sets. Then the pretrained resnet18 model is loaded and its output layer modified for the current scenario. The model is then trained to classify images and its classification accuracy is noted.

*Tools: Numpy, Matplotlib, PyTorch*
