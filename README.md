# Airbnb_price_category_prediction.

# ✔️ Problem Formulation:
We need to predict the price and type of an aparement/house (Target variables) of airbnb company based on its overview summary and image (Independent variables). The price is encoded into 3 classes [0,1,2] so we'll work on it with classification methods. In this problem we can mainly use CONVNETS for images and for the summary overview we can use sequential models like GRU and LSTMs.

The challenges that would be faced could be finding the best way (Model) to deal we both images and text at the same time and of course the hyperparameter tuning.

# ✔️ Strategy used:
Importing libraries and Investigation data
Building a model with CONV Nets
tune the previous model
GRU Model
LSTM Model
Bidirectional LSTMs Model
Work with RGB images instead of grayscale and implement multi-task by predicting both target variables.
Note: Multi-modality is used in all the trials and dropout is used in multiple models.
