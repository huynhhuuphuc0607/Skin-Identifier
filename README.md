# Skin-Identifier

This project uses a Convolutional Neural Network (CNN) to predict the possibility of a skin mole being benign or malignant using the dataset from Kaggle (Link to the dataset: https://www.kaggle.com/fanconic/skin-cancer-malignant-vs-benign). A Classification Report and a Confusion Matrix will be used for evaluation.

The system learns from training samples and makes its best attempt to predict if a future skin mole is dangerous or not. During training, it requires input to be batches of color images of size 224x224. Those of different sizes will be resized to ensure consistency. The output will be probabilities of skin moles being benign or malignant (encoded with 0 and 1, respectively). Those with scores of less than or equal to 0.5 will be classified as benign; otherwise, malignant.
