# DNA Sequence Prediction using Recurrent Neural Network

Prediction of DNA sequences is a common task nowadays. Here, I predicted the classes for each DNA sequence and achieved 99% accuracy on validation set. The npz file contains
data_x(sequences), data_y(classes), validation_x, validation_y and test_x. The task is to predict the classes for test_x. 

The data_x is used for training contains 400 seqences of 400 charachters
Validation_x contains 100 sequences of 1200 charachters


Approach
There are 3 general approaches for this, but we used one hot encoding for each neuclotide. Then we applied simple RNN layers and test the data on validation set.
