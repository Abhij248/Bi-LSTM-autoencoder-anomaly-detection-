The code here is designed for a  14 bus system with the data consisting of 40 columns and multiple rows , each column represents voltage, current or power at one of the nodes. 
The algorithm involves use of Bi-Directional autoencoder model to predict False Data Injection attacks based on reconstruction errors in the input data .
The function "replace_nans()" is optional in the code and is used to tackle NaN data points in the testing data , it replaces the NaN data with the mean value of the column, the function can be removed with proper modification in the code 
The model can be used on google collab or another preferable environment with proper installation of libraries.
