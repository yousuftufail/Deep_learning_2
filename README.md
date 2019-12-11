# Deep_learning_2
In this file I am building two deep learning models on the titanic data set and then compare them. Model_1 has less hidden layers 
and less number of nodes. Whereas, Model_2 is built with more hidden layers and more nodes. I have used validation_split and EarlyStopping with patience=2 on both the models in order to justify the calcuations. Remember EarlyStopping stop the epochs according to patience, 2 in our case.

# important modules
1. pandas
2. numpy
3. Dense from keras.layers
4. Sequential from keras.models
5. to_categorical from keras.utils
6. EarlyStopping from keras.callbacks 

