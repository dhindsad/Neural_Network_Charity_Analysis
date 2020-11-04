# Neural_Network_Charity_Analysis


Overview:
The purpose of this assignment is to create reate a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.


Results:
Preprocessing:
- Is_successful would be the target variable
- Application_type and Income_amount can be used as the feature variables.
- Name and EIN are neither targets nor features, and should be removed from the input data.

Compiling, Training, and Evaluating the Model:
- I used <200 and <1000 application_counts along with two and three hidden neuron layers with various number of hidden nodes. This is to analyze the affect of changing values of these variables on the accuracy outcome.
-I was not able to reach the target model performance as the accuracies for the model were 60,55 and 53.
- I tried increasing the hidden neuron layers as well as removing the columns that can neither be treated as targets not features. 



Summary:
The results summarize that having too many neural networks or having too little will not neccessarily give an accurate outcome. It is neccessary to preprocess the data by removing variables that can neither be used as targets nor feature variablas as having them in our data causes unneccessary bias.
