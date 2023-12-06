# ecg-classification-model
This repository contains MATLAB code covering the training, validation, and testing of an ECG classification neural network 
model based on the GoogLeNet generalist neural network algorithm.

This repository contains code created for the BME3053C final project.

**CHF folder:** Contains ECG data from the BIDMC Congestive Heart Failure (CHF) Database
https://physionet.org/content/chfdb/1.0.0/
Accessed from PhysioNet.org (Goldberger et al., 2000)

**NSR folder:** Contains ECG data from the MIT-BIH Normal Sinus Rhythm (NSR) Database
https://www.physionet.org/content/nsrdb/1.0.0/
Accessed from PhysioNet.org (Baim et al., 1986)

**full model.mlx script:** Contains the translation of ECG data, generation of scalograms through wavelet transform, 
training of the model (saved in trainedModel.mat as trainedNN), validation of the NN, and testing of the NN. 

**ECG_Classification_Model.mlx script:** Generates a set of test CHF and NSR scalogram images and outputs a confusion matrix
quantifying the accuracy of the trained neural network. Additionally, the singleClassification function will allow the user 
to generate their own scalogram by selecting one of the ECG .mat files for visualization of the scalogram and waveform and 
classification of the signal.

**trainedModel.mat:** contains the saved variable 'trainedNN' which is a DAGNetwork (neural network)
