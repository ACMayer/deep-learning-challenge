# deep-learning-challenge
deep-learning-challenge
Module 21

The model that has been designed aims to determine if an Alphabet Soup-funded organisation will be successful based on the features in the dataset. 
This was to be done using a deep learning model and then looked to be optimised.

The variable that indicated if the funding was succesful was classed as "IS_SUCCESSFUL" (binary classification format) and was the targeted variable. 
Variables in data set that didnt contribute had been removed. These where columns such as "EIN" and "NAME".
Featured variables that contributed to the model include but not limited to "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION","USE_CASE" and "ORGANIZATION".

This neural network model has one input layer, two hidden layers and an output layer that had a Sigmoid activation function along with 1 neuron. 
The hidden layers contain 128 and 64 neurons respectively and had a Relu activation function used for them. 
This was selected with the intention to generate a model with enough capacity for the model to effectively analyse the data despite it's complexity.

Originally the model achieved an accuracy of 0.7252 over 100 epochs with a batch size of 28.
I made a series of adjustments to the model in an attempt to improve the models performance, from the number of epochs to changing both cut off values and the batch size. 
I have be unable to achieve a greater accuracy than the one originally achieved. 
Hopefully with more time and a greater understanding of deep learning models I am able to improve the accuracy of this model. 
