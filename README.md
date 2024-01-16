# credit-risk-classification
Supervised Learning Challenge Module 20

by Sungmin Yim

## Credit Risk Analysis Report ##

## Instructions ##
* Split the Data into Training and Testing Sets

* Create a Logistic Regression Model with the Original Data

* Write a Credit Risk Analysis Report

### Split the Data into Training and Testing Sets ###

1. Read the `lending_data.csv` data from the Resources folder into a Pandas DataFrame.

2. Create the labels set (`y`) from the “loan_status” column, and then create the features (`X`) DataFrame from the remaining columns.

    `NOTE:` A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

3. Split the data into training and testing datasets by using `train_test_split`.

### Create a Logistic Regression Model with the Original Data ###
Use your knowledge of logistic regression to complete the following steps:

1. Fit a logistic regression model by using the training data (`X_train` and `y_train`).

2. Save the predictions for the testing data labels by using the testing feature data (`X_test`) and the fitted model.

3. Evaluate the model’s performance by doing the following:

   * Generate a confusion matrix.

   * Print the classification report.

4. Answer the following question:
   
   * How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

### Write a Credit Risk Analysis Report ###
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this module, ensuring that it contains the following:

1. __An overview of the analysis:__ Explain the purpose of this analysis.

2. __The results:__ Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

3. __A summary:__ Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

### References ###
Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
