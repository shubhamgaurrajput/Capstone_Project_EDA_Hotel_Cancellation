# Capstone_Project_EDA_Hotel_Cancellation

# Problem Statement
You have been assigned the task of building an SVM model which can predict the customers who are at risk of cancelling their booking. You need to build a model that can predict the is cancelled column.

# Model Building
# Task - 1
• Do an exploratory data analysis and find out the list of candidate predictors. You can use bivariate plots that measure percentage of canceled bookings across different categories in case of a categorical variable and across deciles in case of continuous variables.
• You will need to use the Json files (details in the data section) to map the values of some of the categorical variables listed in the dataset.

# Task - 2
• You need to experiment with different kernels (linear, RBF, polynomial etc) in the SVM model. In your experiments provide details of:
• The kernel used and the classifier performance on either a single validation set or over folds of data where you have done a cross validation.
• The training times as well as inference times for each hyperparameter you've chosen.
• Justify the model that you finally selected.
• Save your final model by using joblib or pickle.

# Task - 3
• Create a code pipeline to read the saved model and do predictions using that. This should ideally be a separate python file with the logic to load and do inference coded in either a python function or python class.
• Provide your understanding of the next steps that the client/ end-user needs to follow to deploy your model at their end. Think about the below lines:
• Any technical/infrastructure requirements that the client needs to meet?
• What files do you need to provide them?
• What kind of data cleaning and preprocessing would the client need to do before using the model?
• How will the client use your model on new data?
• How will the client know that the model is performing well on new data points?

# Model Validation (Task - 4)
• Use a k-fold validation strategy. You should track either all or a combination of following metrics:
i. AUC
ii. Confusion Matrix
iii. Accuracy
iv. F1 score
