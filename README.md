# Neural Network Charity Analysis
## OVERVIEW

The purpose of the analysis is to create a neural network model (binary classifier) that is able to predicting whether applicants will be successful if funded by Alphabet Soup. In order to properly complete the analysis we have to: 1.Preprocess the data for the neural network, 2.Compile,train and evaluate the model & 3.Optimize the model.

## RESULTS
### Data Preprocessing

- What variable(s) are considered the target(s) for your model?

The IS_SUCCESSFUL column.

- What variable(s) are considered to be the features for your model?

Every column except the ones that we will drop.

- What variable(s) are neither targets nor features, and should be removed from the input data?

'EIN' & 'NAME'

### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?

There is an input features & two hidden layers in this model. The first hidden layer has 80 neurons, the second has 30, and there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer's activation fuction is "sigmoid".

- Were you able to achieve the target model performance?

Unfortunately no. 

- What steps did you take to try and increase model performance?

I tried adding hidden layers, changing # of epochs, changing activation types, and changing the number of neurons in each layer.

## SUMMARY
Overall, the model's accuracy was close to 73% (72.8%). It is close to the 75% accuracy but not close. I believe that more features that are not necessarily impactful to the analysis could've been dropped and that would've made the model more accurate since there would be less data for points of deviation from the actual purpose of the model. However, we could've also had more data specific to the analysis. 
