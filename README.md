# EEG-3D-CNN
ECE247 Project: Classification of Motor Imagery EEG data using CNN and RNN
Aki A. Kono, Bryan Lee 

## DataSet
http://www.bbci.de/competition/iv/desc_2a.pdf

## Abstract:
Two classifiers are developed to classify Motor Imagery electroencephalography (EEG) data; the classifier based on CNN structure and the classifier that combines CNN and RNN structure. In the first approach, a deep 2D CNN was combined with a shallow 3D CNN to extract spatiotemporal features of the data. Data augmentation was proven to be effective and increased test accuracy by 13%. In the second approach, an autoencoder was optimized with respect to its latent dimension and the data was encoded to reduce their spacial dimensions. The model with purely CNN structure resulted in the highest test accuracy of 78% compared to 67% of the CNN-RNN structure.

For more details, please read EEG_Project.pdf.
