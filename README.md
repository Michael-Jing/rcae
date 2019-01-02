# Robust Convolution AutoEncoder for Anomaly detection [rcae]
contains the code and datasets used  for models in the paper [Robust, Deep and Inductive Anomaly Detection](https://arxiv.org/pdf/1704.06743.pdf)

The python files with _CAE.py contains Convolution Autoencoder network architecture 
while python files with _AE contains Autoencoder network architecture used for models in the paper

# What is working
The section_5.1_anomaly_detection_Restaurant_cae.py is now working.
I implemented the custom regression_RobustAutoencoder layer based on my understanding 
of the paper. When the noise term N equation 6 is fixed, the first part of the equation 
is implemented using standard mean squared error, and, the second part of the equation 
is implemented as L2 normalization
