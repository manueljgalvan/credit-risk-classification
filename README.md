# credit-risk-classification

**Requirements**

**Split the Data into Training and Testing Sets (30 points)**
To receive all points, you must:
Read the lending_data.csv data from the Resources folder into a Pandas DataFrame. (5 points)
Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns. (10 points)
Split the data into training and testing datasets by using train_test_split. (15 points)

**Create a Logistic Regression Model (30 points)**
To receive all points, you must:
Fit a logistic regression model by using the training data (X_train and y_train). (10 points)
Save the predictions on the testing data labels by using the testing feature data (X_test) and the fitted model. (5 points)
Evaluate the model’s performance by doing the following:
Generate a confusion matrix. (5 points)
Generate a classification report. (5 points)
Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels? (5 points)

**Write a Credit Risk Analysis Report (20 points)**
To receive all points, you must:
Provide an overview that explains the purpose of this analysis. (5 points)
Using a bulleted list, describe the accuracy, precision, and recall scores of the machine learning model. (5 points)
Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. (10 points)

**Coding Conventions and Formatting (10 points)**
To receive all points, you must:
Place imports at the top of the file, just after any module comments and docstrings and before module globals and constants. (3 points)
Name functions and variables with lowercase characters, with words separated by underscores. (2 points)
Follow DRY (Don’t Repeat Yourself) principles, creating maintainable and reusable code. (3 points)
Use concise logic and creative engineering where possible. (2 points)

**Code Comments (10 points)**
To receive all points, your code must:
Be well commented with concise, relevant notes that other developers can understand. (10 points)

## Results of the Analysis

 Below is a description of logistic regression model accuracy, precision, and recall scores that the analysis produced.

 * Accuracy: The overall accuracy of the model is 0.99, indicating that it correctly classifies 99% of the instances analyzed.

 * Precision
   * Healthy Loan classified as (class 0): 1.00
   * High-Risk Loan classified as (class 1): 0.87
  
 * Recall
   * Healthy Loan classified as (class 0): 1.00
   * High-Risk Loan classified as (class 1): 0.95
  
     ## Summary

The logistic regression model performs very well in predicting healthy loans (class 0), achieving a precision of 1.00 and recall of 1.00. For risky loans (class 1), the model’s performance is still strong, with a precision of 0.87 and a recall of 0.95.

The model is very accurate at predicting healthy loans (labeled as 0) and performs well on this category, with almost perfect accuracy in identifying these loans correctly. For high-risk loans (labeled as 1), the model does a good job too, but it's not as precise. While it can identify high-risk loans fairly well, it’s less consistent at catching every high-risk loan compared to healthy ones. This means there’s still some room to improve in recognizing high-risk loans accurately.
