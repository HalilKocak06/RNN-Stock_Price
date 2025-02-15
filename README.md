### Overview
# Goal: Predict the daily opening price of Google’s stock using a Recurrent Neural Network (RNN) with LSTM layers.
# Approach:
# Data Preprocessing: 
Load the dataset, scale features, and create 60-day time windows for training.
# Model Building: 
Stack four LSTM layers with Dropout regularization to prevent overfitting.
# Training: 
Compile the model with the adam optimizer and mean_squared_error loss, train for 100 epochs.
# Evaluation: 
Predict on the test set, compare with the real stock prices, and visualize.
