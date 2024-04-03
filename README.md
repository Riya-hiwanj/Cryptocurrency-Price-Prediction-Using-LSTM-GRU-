# Cryptocurrency-Price-Prediction-Using-LSTM-GRU-
 Methodology
 
 Create a time series dataset, ensuring sequential order.
 Considering Moving Averages, Lag plots to define input features and target variable (Close Price).
 Split the dataset into training and testing sets using MIN-MAX Scaling
 Build LSTM and GRU models using TensorFlow
 compiling model using the Adam optimizer and the mean squared error as the loss function.
 Set up ModelCheckpoint callback to monitor the validation loss (val_loss) during training.  It will save the model's weights to the specified file
 Set up an EarlyStopping callback, If there is no improvement in validation loss for a specified number of epochs (in this case, patience=10), training will stop early.
