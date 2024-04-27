The purpose of this project was to evaluate the performance of 3 different classification models: Logistic Regression, Random Forest, & Gradient Boosting, with the end goal of predicting customer fraud. 
The data set contained 27 columns and 125000 rows, with the variable of interest being 'EVENT_LABEL' indicating 'fraud' or 'legit'.
Exploratory data analysis was performed to understand any trends and patterns in the data to help with feature selection. Data preprocessing involved handling missing values and encoding categorical variables.
Initial models were built and then parameter tuning was performed using regularization (Logistic) or GridSearch (RF and GB) for optimizing the model parameters. 
After the best parameters were selected, the models were evaluated by comparing the Accuracy, Precision, Recall, and AUC of the test data set. 
Finally the best model was selected and used to predict a hold out data set. The final deliverable included an executive summary report for a business audience.
