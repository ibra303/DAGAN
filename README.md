# DAGAN
This repository contains materials for a seminar on the 2017 paper "Data Augmentation Generative Adversarial Networks" by Antoniou, Storkey, and Edwards (arXiv:1711.04340). The seminar covers the key concepts, methodology, and implications of the DAGAN model, which uses generative adversarial networks to enhance datasets through synthetic data generation. Additionally, this repository includes scripts for training the DAGAN model on the OMINGLOT dataset


# Contents
* Offical paper and seminar slides
* Script for training the DAGAN model on the OMNIGLOT dataset
* Instructions for setting up the environment and running the experiment
* Results of the model's performance
  

# Setup and running the training
1. Download the ipynb file and upload it to Google Colab
2. set up your drive folder to save checkpoints for the model training
  * Mount your Google Drive in the Colab notebook.
  * Specify the directory in Google Drive where checkpoints will be saved.
    
Note: Training can take a significant amount of time. We recommend using a V100 or A100 GPU runtime for optimal performance.

# Trainig results
* Epoch 3
  
 ![image](https://github.com/ibra303/DAGAN/assets/94124916/e7caffa2-f8b7-450a-bc86-f4093680b6a6)
* Epoch 8
  
 ![image](https://github.com/ibra303/DAGAN/assets/94124916/50e49058-83cd-402e-95bb-16ac7656f341)
* Epoch 14
  
 ![image](https://github.com/ibra303/DAGAN/assets/94124916/4cd48fba-9e1c-42d1-b848-ae0e235dfdfb)
* Epoch 19
  
 ![image](https://github.com/ibra303/DAGAN/assets/94124916/fd030d3f-1a7b-4335-8c27-2b3b3638a15d)




