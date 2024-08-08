# Deep Learning Neural Network
# Overview 
This neural network analyzes organizations applying for funding through the Alphabet Soup Nonprofit. The model predicts the likelihood of success for each grant.

# Data Preprocessing
- Model Target: "IS_SUCCESSFUL" column
- Model Features: all other columns except the ID's
- Variables removed: ID columns

# Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?   
The initial model has two hidden layers with 9 nodes for layer one, and 3 nodes for layer two, while sigmoid and relu activations were chosen based on their design for binary predictions. 100 epochs were chosen based on class activities.

# What steps did you take in your attempts to increase model performance?
# Optimization 1
The initial run included 2 hidden layers, relu & sigmoid activation, with 100 epochs.
Results:
- Loss: 55.4%
- Accuracy: 72.2%

# Optimization 2
The change was adding more neurons to the existing hidden layers to identify whether the previous model was oversimplifying.
Results: 
- Loss: 55.8%
- Accuracy: 72.1%

# Optimization 3
The change was adding "elu" as the activation instead of "relu" to avoid the dying relu problem.
Results:
- Loss: 55.5%
- Accuracy: 72.4%

# Application
Stakeholder opinion would be needed to determine whether this model is fit for deployment. The non-profit would need further risk analysis for the loss of more than 25% of it's investments having unexpected outcomes.

