# deep-learning-challenge
### Overview
Help select the applicants for funding with the best chance of success using machine learning and neural networks.

### Target variable
IS_SUCCESSFUL
### Features

- NAME 
- APPLICATION_TYPE
- AFFILIATION
- CLASSIFICATION 
- USE_CASE
- ORGANIZATION
- STATUS
- INCOME_AMT
- SPECIAL_CONSIDERATIONS
- ASK_AMT

### Removed from the input data
EIN

### Neural network model
- 3 layers
- Adjusted number of neurons to improve accuracy
- Activation: relu

### Adjustments that increases model performance
- Added an additional group of bins
- Added a third layer to the model
- Decreased the number of neurons per layer

### Summary
After three iterations of adjusting the model I was able to get the accuracy to 79% (above the 75% threshold). Adding NAME to the features helped with accuracy due to the correlation between the name of the organization and the amount of donations received. 