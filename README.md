# Neural_Network_Charity_Analysis

The Purpose of the analysis is to use neural network to decide which companies should receive loans from Alphabet Soup.


Results


Data Preprocessing

After looking at the data, I established that the target variable is the "IS_SUCCESSFUL" column. I then removed the "EIN" and "NAME" columns as they did not offer any relevant data that could help the model perform better. 

Compiling, Training and Evaluating Model

Both layers had relu activation functions and the output layer had a sigmoid activation function. I started with these parameters as relu does better with nonlinear data, and two layers allows for a second layer to reweight the inputs from the first layer. Here are the performance metrics of this model.

268/268 - 0s - loss: 0.5505 - accuracy: 0.7325
Loss: 0.5505281090736389, Accuracy: 0.732478141784668

I tried another two attempts with adding another one and two layers at a time and using 6 and 8 neurons respectively but could not more than 74% accuracy.


Summary

This is potential becasue I got rid of too many columns, I did not use the correct activation function, or I did not have hte right amount of layers and neurons. These were the main areas I continued the change with little to no improvement.
