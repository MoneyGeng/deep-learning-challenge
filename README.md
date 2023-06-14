# deep-learning-challenge - Module 21

# Deep Learning Model Performance Report

Overview of the Analysis: The objective of this project is to develop a machine learning algorithm using neural networks to forecast the likelihood of applicants' success if they receive funding from the fictional non-profit organization, Alphabet Soup.
Data Preprocessing:

- Target Variable(s): The target variable for the model is "IS_SUCCESSFUL," which indicates whether the funding provided by Alphabet Soup was used effectively.
- Feature Variable(s): The feature variables for the model include the following columns: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
- Variables to Remove: The EIN and NAME columns are removed from the input data as they are identification columns and do not provide relevant information for the model.
Compiling, Training, and Evaluating the Model: Three deep learning models were trained and evaluated:
## Model 1:
- Architecture: This model consists of two hidden layers with 9 and 18 nodes, respectively, using the ReLU activation function. The output layer has 1 node with the sigmoid activation function.
- Model Performance: The model achieved a loss of 0.5520 and an accuracy of 0.7265 on the test data.
- 
## Model 2:
- Architecture: This model includes three hidden layers with 12, 24, and 1 node, respectively, using the ReLU activation function. The output layer has 1 node with the sigmoid activation function.
- Model Performance: The model achieved a loss of 0.5514 and an accuracy of 0.7276 on the test data.

 
## Model 3:
- Architecture: This model consists of two hidden layers with 9 and 18 nodes, respectively, using the hyperbolic tangent (tanh) activation function. The output layer has 1 node with the sigmoid activation function.
- Model Performance: The model achieved a loss of 0.5533 and an accuracy of 0.7245 on the test data.

 
# Summary: 
In summary, three deep learning models were trained and evaluated to predict the success of applicants funded by Alphabet Soup. Model 2 achieved the highest accuracy of 72.76% on the test data, slightly outperforming Model 1 and Model 3. These models provide a solid foundation for predicting the effectiveness of funding for future applicants.
To further improve the model's performance, additional experimentation and optimization can be performed, such as adjusting the number of nodes and layers, trying different activation functions, and exploring different neural network architectures. 



