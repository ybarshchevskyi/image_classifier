# Flower Image Classifier

## Project Description

This project is part of Udacity PyTorch Scholarship Challenge. More details on the scholarship could be find here - https://www.udacity.com/course/deep-learning-pytorch--ud188

In this project, the task is to train an image classifier to recognize different species of flowers. Detailed dataset description is provided here - http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html. It consits of 102 flower categories. 

PyTorch is used for the model training. With the code provided, you can replicate the process and train your own image classification model using any of pre-trained features from - https://pytorch.org/docs/stable/torchvision/models.html

## Repository description 

  ### Dataset
  To load dataset, please follow this link - https://s3.amazonaws.com/content.udacity-data.com/courses/nd188/flower_data.zip
  
  The dataset is split into the training and validation sets. You can use different folder names. In this case, just make  changes to the file path in "Image Classifier" notebook. 
  
  ### Notebooks
  In order to train your model, you will need to build a classifier from "Image Classifier" notebook. Please follow the instructions provided in this notebook. 
  
  "Model testing" notebook contains prediction function to test your model performance on a single image.  
  
  ### JSON object
  
  "cat_to_name" JSON-file has text labels for all 102 image classes. 
  
## Installation

To run the code, please install the following dependencies:

  - PyTorch
  - NumPy
  - Matplotlib
  - Seaborn
  
 ## Licensing, aknowledgements
 
 A big credit is given to the Udacity PyTorch challenge. You cannot use this repository as part of your Udacity Deep Learning program. Otherwise, feel free to experiment with the code provided. 
