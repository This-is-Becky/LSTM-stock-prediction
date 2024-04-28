# LSTM Stock Trend Prediction Model
## Overview
This repository contains code for training and evaluating an LSTM (Long Short-Term Memory) model to predict stock trends. The model's performance metrics on both the training and test datasets are detailed below.

## Model Performance
### Training Data:
* Mean Squared Error (MSE): 0.00075
* R-squared (R²): 0.988
* Accuracy: Approximately 98%

### Test Data:
* Mean Squared Error (MSE): 0.0002
* R-squared (R²): 0.974
* Accuracy: Approximately 97%
  
These metrics demonstrate that the model learned well from the training data and performed well on unseen test data, achieving high accuracy in predicting actual stock values.

### Stock Trend Prediction
After training the LSTM model, predictions were made for the next 7 days of stock trends. The model indicated a decreasing trend. Upon observation, the actual stock prices did indeed decrease gradually over the next 7 days.

## Note
* Important: This repository serves as an example of applying LSTM for stock trend prediction. It is not recommended or suggested for use in real-world financial investigations or decisions.
