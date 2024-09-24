#Multiclass Text Classification using CNN
#Overview
This repository implements a Convolutional Neural Network (CNN) for multiclass text classification. The model is designed to classify text data into multiple categories based on its content.
Here I am using the products_clean.csv

#Features
. Multiclass classification: Handles more than two output classes.
. CNN architecture: Uses convolutional layers to extract features from the input text.
. Preprocessing: Tokenization, padding, and text vectorization.
. Model evaluation: Includes metrics like accuracy, precision, recall, and F1-score.

#Model Architecture
The CNN model consists of the following layers:

1) Embedding Layer: Converts the input text into dense vector representations.
2) Convolutional Layers: Extracts local features from the text.
3) MaxPooling: Reduces the dimensions of the feature maps.
4) Fully Connected Layers: Performs the final classification.
