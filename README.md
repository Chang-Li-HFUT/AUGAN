# AUGAN
Code for paper: Plane-Wave Image Reconstruction via Generative Adversarial Network and Attention Mechanism
## About the paper
* Title: [Plane-Wave Image Reconstruction via Generative Adversarial Network and Attention Mechanism](https://ieeexplore.ieee.org/abstract/document/9449652)
* Authors: Jiahua Tang, Zou Bao, Chang Li, Shuai Feng, Hu Peng 
* Institution: Hefei University of Technology
* Published in: IEEE Transactions on Instrumentation and Measurement
## Instructions
* Before running the code, please download the PICMUS dataset, unzip it and place it into the right directory(cubdl_master/datasets). The dataset can be found [here](https://www.creatis.insa-lyon.fr/Challenge/IEEE_IUS_2016/download). 
Six types of plane-wave image dataset
+simulation_resolution_distorsion_iq
+simulation_contrast_speckle_iq
+experiments_resolution_distorsion_iq
+experiments_contrast_speckle_iq
+experiments_carotid_long_iq
+experiments_carotid_cross_iq
Each .mat data file contains the consponding single plane_wave image.  
* Please run the dataset.py to load the .mat data file and modify the parameters acquisition_type, phantom_type and data_type to generate the training data and test data.
* Using train.py to train the model and test.py to test the model ,  
## Requirements
+ Pyhton3.6
+ pytorch-gpu (1.6.0 version)

If you have any questions, please contact 2019110062@mail.hfut.edu.cn

## Reference
* [Challenge on Ultrasound Beamforming with Deep Learning (CUBDL)](https://gitlab.com/dongwoon.hyun/cubdl)
