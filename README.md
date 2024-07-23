# Deep Learning Neural Network
# Overview 
This neural network analyzes organizations applying for funding through the Alphabet Soup Nonprofit. The model predicts the likelihood of success for each grant.

- Preprocessing -
The data is preprocessed by dropping ID columns, simplifying features within the application types, and sorting classification fields. Categorical data is encoded while numeric data is scaled before testing and training groups are split. The target column can be identified as "IS_SUCCESSFUL". 

- Evaluating the Model -
The final model has two hidden layers with 9 nodes for layer one, and 3 nodes for layer two. The goal in mind was 75% which was not achieved after several shifts. Previous iterations included more nodes on layer 2 and nadam vs adam optimizers with no significant change in result.

- Results
Loss: 55%            
Accuracy: 72%
Epochs: 100

# Application
I would not recommend using this model before further troubleshooting for higher accuracy and efficiency. 

# Usage
