# Deep-Learning

**Data preparation**
In preparing the data I have removed the NAME, EIN & STATUS columns since those are not relevant to the deep learning model we are implementing.
The target for the model is the success of the funding or IS_SUCCESSFUL
The remaining columns are considered to be features (APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT)

**Compil,Train and Evaluate Model**
For the model, I have decided to use two hidden layer with 8 and 16 nodes with Sigmoid and Relu activation respectively. For the output layer I have chosen to use Sigmoid activation functions. This resulted in an accuracy of 0.7321 which is faily close to the 75% accuracy goal.
