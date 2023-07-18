# deep-learning-challenge
OVERVIEW: The purpose of this project is to explore deep learning and understand how the model hyperparamenters affect the model fit

Data Preprocessing: 
- The target variable for this model is the "IS_SUCCESSFUL" column which alludes to whether the money from the funding was use effectively. 
- The Features of the model included the alphabet soup application type, the affiliated sector of industry, the government organization classification, the organization type, the active status, the income clasification, and the ask amount.
- The items that were removed due to them not being features or targets were the EIN, the NAME column. And the Special Considerations and Use case were also removed for optimization attempts.

Compiling, Training, and Evaluating the Model:
- I chose to use 4 layers with a pattern of decreasing neurons for each layer becuase that seemed to help increase the accuracy of the model
- I was not able to achieve the target performace of 75%. 
- I attampted changing the target fields by removing some columns, but more often than not this reduced accuracy. I attempted adding neurons and layers, and this seemed to add accuracy. I also changed around the activation function of the layers and this seemed to change the loss, but not the accuracy as much. Finally, I changed the amount of epochs and this also seemed to increase the accuracy.

Overall, the deep learning model was able to predict the "Success" of funding with an accuracy of 73%. Using the random forest feature importance tool, we could limit the data to just the features that are above a certain importance. THis is just one way to more mathematically attempt to increase the accuracy of the model. 