# Offensive-Language-Detection-using-Backpropagation
Simple neural network to detect offensive language usage


# Topic
The dataset for this project is obtained from twitter and contains instances of hate speech, offensive language and neither. Seen as I wanted to try with binary classification
I will only use the offensive speech and the non offensive to create two classes for the target. The dataset contains labeled text which I will first process and then 
train a simple neural network to capture the difference between the two kinds of speechs.


# Summary
- Importing libraries
- The dataset
- Converting characters to lower case
- Removing punctuation
- Removing digits
- Tokenizing sentences
- Removing stopwords
- Removing frequent words
- Stemming
- Bag of words
- Train/Test split
- Creating train/test loaders
- Building the classifier
- Training and inference
- Trying out the model
- Conclusion


# Libraries
- Pandas
- Numpy
- Torch
- NLTK
- SKlearn


# Data source
https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset?fbclid=IwAR2kOFFLqhMQrV_K1ThWbpWG21WGPqyn4HOsiLzR3vsXMkQw1rgH9MxGGuc
