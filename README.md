# Neural_Network_Charity_Analysis
                                       Foundation Investment prediction
                                       
## Overview of the Analysis
The purpose of this project is to create a classifier that would predicte whether are successful once they received funds by Alphabet Soup foundation. 

We use the data provided by the foundation (charity_data.csv) that contians historical information about the applicants. 

 Using Neural Network to analyze the charity, we targeted the (Is_Successful) column as it is indicate if the money used to serv the purpose or not.
 Model Features: NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, ASK_AMT. 

Non benifical variables removed are EIN (Employer identificaiton). A SPECIAL_CONSIDERATIONS column can be dropped as there is only few rows with special considerations as (Y) as a result this creates imbalance in the values and can not be considered.

# Compiling, Training, and Evaluating the Model

In this model there are three hidden layers each with many neurons, because this seeemed to increased the accuracy above 75%. The number of epochs wasn't changed. The first activation function was 'relu' but the 2nd and 3rd were 'sigmoid'and the output function was 'sigmoid'. Changing the 2nd and 3rd activation functions to 'sigmoid' also helped boost the accuracy.

