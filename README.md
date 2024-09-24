**Text Classification using CNN**

**Overview**

This repository implements Convolutional Neural Networks (CNNs) for both multiclass and binary text classification. The models are designed to classify text data into multiple categories based on its content.

**Datasets**

**1. Multiclass Classification**
    Dataset: products_clean.csv
    Code: multiclass_text_Classification.ipynb
    Description: This dataset contains product descriptions and is used to classify texts into multiple categories.
   
**2. Binary Classification**
    Dataset: newdataset1.csv
    Code: text_Classificaton(Binary class).ipynb
    Description: This dataset is utilized for binary classification tasks based on the text content.
   
**Features**

. Multiclass classification: Handles more than two output classes.
. CNN architecture: Uses convolutional layers to extract features from the input text.
. Preprocessing: Tokenization, padding, and text vectorization.
. Model evaluation: Includes metrics like accuracy, precision, recall, and F1-score.

**Model Architecture**

The CNN model consists of the following layers:

1) Embedding Layer: Converts the input text into dense vector representations.
2) Convolutional Layers: Extracts local features from the text.
3) MaxPooling: Reduces the dimensions of the feature maps.
4) Fully Connected Layers: Performs the final classification.
