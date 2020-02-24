fittnussDNN
========================

This is a code for performing inverse analysis of tsunami deposits using deep-learning neural network. The forward model fittnuss produces datasets of the thickness distribution of tsunami deposits with random initial conditions, and DNN constructed with tensorflow and keras learns the relation between initial conditions and depositional features. Then, the trained DNN model works as the inverse model for ancient or modern tsunami deposits. See details in Mitra, Naruse and Abe (2020).

---------------
Explanation of files

fittnuss.py:
the forward model for deposition from tsuanmis

DNN_Tsunami_inverse_model.ipynb:
a jupyter notebook for performing the inversion

start_param_random_5000_g6_300grid_19_11.csv:
teacher data. Initial conditions used for production of training datasets.

eta_5000_g6_300grid_19_11.csv:
training and test data produced by the forward model. This file is too large to store in GitHub, so that it is only available from Zenodo repository.

sendai_increased_class_edit.csv:
Data of 2011 Tohoku-Oki tsunami deposit measured in the Sendai Plain. Volume-per-unit-area of 6 grain size classes were recorded.

config_g6_300grid_19_11_case2.ini:
Configuration file of the forward model used for production of the training datasets and inversion.

---------------
Usage


----------------
Example
