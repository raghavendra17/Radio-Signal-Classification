# Radio-Signal-Classification

## Problem Statement
* Build a model using CNN for classifying the radio signals from deep space using Keras from the SETI Dataset

## Dataset Description
* The dataset consists of 2-Dimensional spectrograms of radio signals from space collected at the SETI Instituteby the Allen Telescope Array.
* The objective is to classify the radio signals from outer space into one of four classes
### SETI Dataset
#### Training Data:
   * train_images: Normalized values of Pixels 
   * train_labels: Stored as One-Hot Encoded data
#### Validation Data: 
   * val_images: Normalized values of Pixels 
   * val_labels: Stored as One-Hot Encoded data
#### Classes: “squiggle”, “narrowband”, “narrowbanddrd”, and “noise”

## Steps to Build Model
* Import Required Libraries
* Load the data using pd.read_csv 
* Check the shape of the training and validation data 
* Check the data distribution
* Preprocess the data
  * Convert into numpy array and reshape the training and validation images
* Visualize the dataset
* Create Training and Validation Data Generators using Keras ImageDataGenerator function
* Design a Convolutional Neural Network (CNN) Model
* Compile the Model using Adam optimizer, categorical_crossentropy loss function, and accuracy metric
* Print the Model summary
* Train the Model with batch_size = 32 & epochs = 12 
* Evaluate the Model 
* Print a Classification Report and the accuracy score (classification accuracy)
* Display a Confusion Matrix to evaluate the performance of the model

