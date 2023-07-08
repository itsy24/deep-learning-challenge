# Alphabet Soup
## Overview:
To streamline the process of selecting funding applicants that ensure the best chance of success in their ventures.


Results: 

Data Preprocessing
- Target variable: IS_SUCCESSFUL column
- Features variables: NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, & ASK_AMT columns	
- Variable(s) that should be removed from the input data because they are neither targets nor features: EIN
  
Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
- The parameters for this model were chosen with the help of the keras tuner. Doing so allows for the best model to be found for this dataset. 
  
- Were you able to achieve the target model performance?
   No, the model's accuracy was at 75.6%.
- What steps did you take in your attempts to increase model performance?
  Including the name column as a feature help increase the accuracy. Not including the column had an accuracy of 72%. 

Summary: 
Overall, the model is able to accurately discern a possible successful venture 75.6% ; however, the loss was at 50%. 
Rather than changing the model entirely, more data and subtle tweaks to the model may help increase the accuracy, figuing out how to lower the model's loss would also be beneficial.

