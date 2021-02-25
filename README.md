# LiCNN_Models

This repo contains scripts which we use for predicting the percentage of Lichen within a microplot.

CCMEO Lichen Predict is the script which uses the trained LiCNN neural network to predict the lichen % of ground photos.

CCMEO Lichen Training is the script used for training the LiCNN Neural network.

CCMEO_Microplot_Clipper_Script is the script used for clipping field photos to the inside of the microplot. 

LiCNN_Env and RTX_LiCNN_Env are 2 environment files used for creating an anaconda environment to use the scripts. RTX_LiCNN_Env works best on 3XXX Nvidia RTX GPUS, while LiCNN_Env should work on most other computers.

lichen_all_v2.h5 is currently the best trained LiCNN model weights. These weights have been trained with datasets of lichen photos across Canada. 
