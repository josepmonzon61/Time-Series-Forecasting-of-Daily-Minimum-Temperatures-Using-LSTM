Description

This project implements a deep learning model to forecast daily minimum temperatures using a Long Short-Term Memory (LSTM) network. The dataset, sourced from the Daily Minimum Temperatures dataset, contains daily temperature observations from Melbourne, Australia, spanning from 1981 to 1990.


The project demonstrates the following key steps:


Data Preparation:

Download and parse the dataset.
Split the data into training and validation sets.
Window the dataset for sequence prediction.


Model Architecture:

Create a sequential model with Conv1D and LSTM layers.
Use the Huber loss function and the Adam optimizer.


Training:

Adjust the learning rate using a learning rate scheduler.
Implement early stopping to prevent overfitting.
Train the model on the windowed dataset.


Evaluation:

Forecast temperatures on the validation set.
Compute and display Mean Squared Error (MSE) and Mean Absolute Error (MAE).
Visualize the actual vs. predicted temperatures.
The project code is written in Python, utilizing TensorFlow for model creation and training, and Matplotlib for data visualization. This repository provides a comprehensive guide to time series forecasting using LSTM, emphasizing the importance of early stopping to enhance model performance.
