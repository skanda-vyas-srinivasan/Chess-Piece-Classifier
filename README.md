# Chess Piece Classifier

A Neural Network classifier that is used to classify images of chess pieces

## Programming Languages/Libraries/Frameworks

TensorFlow, Python, Keras

## Data

A dataset from Kaggle, which contains images of chess pieces. 

**Chess Pieces Dataset (85 x 85)**

Link : https://www.kaggle.com/datasets/s4lman/chess-pieces-dataset-85x85

## Project Description

This project in essence, uses a Convolutional Neural Network in order to classify images of chess pieces to their respective labelS. The classifier is enabled to detect whether a particular piece is a pawn, knight, bishop, queen or a king.


#### Model Architecture

The model at hand uses 3 convolutional layers in order to extract features of the data, followed by Pooling. Batch Normalization is done after each convolution in order to accelerate convergence. Once the preprocessing is done, the pixels are flattened and passed into the Neural Network. It is then followed by three layers of Neurons with 'relu' activation, followed by a final dense layer with a softmax activation corresponding to the output

<div align="center">
  <img src = "https://github.com/golgiwaffles/Chess-Piece-Classifier/blob/main/Chessmodel.h5.png" width = "137px" height = "1396px" />
</div>

##




