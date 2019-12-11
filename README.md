# Deep_learning_2
In this file I am building two deep learning models on the titanic data set and compare these models. Model_1 has less hidden layers 
and less number of nodes. Whereas, Model_2 has more hidden layers and more nodes. I have used validation_split and EarlyStopping with 
patience=2 on both the models in order to justify the calcuations. Remember EarlyStopping stop the epochs according to patience, 2 in our case.

# important modules
pandas
numpy
Dense from keras.layers
Sequential from keras.models
to_categorical from keras.utils
EarlyStopping from keras.callbacks 

