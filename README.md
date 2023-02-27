# Product-Failure-Test

This project is from kaggle. It contains 18 measurement features and 4 attributes .

I managed to make data proccessing including 
-managing the null values either for continuous data by taking the mean values or for categorical values by filling with unknown category
-scalling the data
-creating one hot encoding for categorical data

I made feature selection using statistical model GLM and filtered the features using the most significant ones (p-value < 0.05)

I used a deep neural network model containing four layers then converted the output to be categorical ones as the neural network gives continues data
