# Project1 : Sign Language Detector
### This project is all about detecting some of the basic hand signs made by people who can't hear or can't speak.
## Step 1 : Installing required tools for Object Detection
Watch the youtube video by Nicholas Renotte to get the in-depth idea about the installation.
Link - https://youtu.be/dZh_ps8gKgs
## Step 2 : Downloading models from Tensorflow Model Zoo
Go to root directory and run the following command in cmd.

    mkdir MLSignDetection && cd MLSignDetection && mkdir Tensorflow && cd Tensorflow && git clone https://github.com/tensorflow/models
## Step 3 : Dataset collection and labelling

Store all images in the images folder. Run the code to make images folder.
Dataset can be found on kaggle.

Example: Hand dataset link - https://www.kaggle.com/datasets/shyambhu/hands-and-palm-images-dataset

    mkdir workspace && cd workspace && mkdir images
Install labelImg to label images

    pip install labelImg && labelImg
To label images:

 1> Click on Open Dir and select the images folder.
 
 2> Click on Change Save Dir and select the same images folder.
 
 3> Now select the image from right panel and press w to start labelling.
 
 4> Drag the cursor on the portion to be labelled and save it.
 
## Step 4 : Split the dataset into train and test
Create train and test folder inside images folder and transfer 70-80% images and corresponding xml file of each category(if more than one type of image link hand, foot, etc.) in train folder and rest in test folder.
 
       
