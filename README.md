# EEG-3D-CNN
ECE247 Project: Classification of Motor Imagery EEG data using CNN, RNN, and Autoencoder
Aki A. Kono, Bryan Lee 

## DataSet
http://www.bbci.de/competition/iv/desc_2a.pdf

## Abstract:
Given electroencephalography (EEG) data and their labels, the paper compares two approaches for building a best classifier for the data. In the first approach, a deep 2D CNN was combined with a shallow 3D CNN to extract spatiotemporal features of the data. Data augmentation before training the combined classifier was proven to be effective and increased test accuracy by 13%. In the second approach, an autoencoder was optimized with respect to its latent dimension and the data was encoded to reduce their spacial dimensions and improve test accuracy. The processed data was used to train a combination of a CNN and RNN classifier. In conclusion, the model with purely CNN structure resulted in higher test accuracy of 78% compared to 67% of the CNN-RNN structure.

For more details, please read EEG_Project.pdf.
