# Perceptron-Algorithm
Implementation of Perceptron Algorithm on Banknote dataset

# Data Set Information:

Data were extracted from images that were taken from genuine and forged banknote-like specimens.
For digitization, an industrial camera usually used for print inspection was used.
The final images have 400x 400 pixels.
Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained.
Wavelet Transform tool were used to extract features from images.

--------------------------------------------------------------

# Formulas:

- Y-hat = W.T * X

- General Formula:

     W =: W + n * X * ( Y - Y-hat )


- Move the line UP:

     Wi =: Wi - n * Xn


- Move the line DOWN:

     Wi =: Wi + n * Xn
     
     
n : Learning Rate

W : Weights Matrix

Y : Labels

X : Data Matrix

--------------------------------------------------------------

# mean_squered_error function.

we use the Mean Squered Error to calculate the error the model

MSE = 1/m * sum( pow( (target set - predictions set) , 2) )

m: the number of rows of the sets

--------------------------------------------------------------

# relations between the features.

![download](https://user-images.githubusercontent.com/83607748/184507187-3c782fc8-41d3-427a-b988-83313340b852.png)


