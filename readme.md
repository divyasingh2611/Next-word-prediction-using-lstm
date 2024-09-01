LSTM Text Prediction Model
This repository contains a Long Short-Term Memory (LSTM) model implementation for predicting the next word in a sequence using Keras and TensorFlow.

Overview
This project was originally developed in a Google Colab notebook and focuses on text prediction using an LSTM model. The model is trained on a dataset of article titles, and it aims to predict the next word given a sequence of words.

Requirements
Python 3.x
TensorFlow
Pandas
NumPy
Dataset
The dataset used for this project consists of article titles and is available here.

Installation
To install the required libraries, you can use pip:
pip install tensorflow pandas numpy

Usage
1. Data Preparation
The script starts by loading the dataset from a CSV file located on Google Drive. The dataset contains titles of articles.

2. Data Preprocessing
Text data is cleaned by converting to lowercase, removing punctuation, and trimming extra spaces.

3. Model Architecture
The LSTM model is built using several layers:

Embedding: For word embeddings.
LSTM: Long Short-Term Memory layer.
Dense: Fully connected layer.
Bidirectional: Wraps the LSTM for better context understanding.
4. Training the Model
The model is compiled and trained using the Adam optimizer and categorical crossentropy as the loss function.

5. Predictions
After training, the model can be used to predict the next word in a sequence.
