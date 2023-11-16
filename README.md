# Credit-risk-classification

# Split data into Training and Testing

  I first created a path to read the CSV and then transformed the CSV into a DataFrame. To create my "y" label which going to be the 'load_status' column I made a "y" variable and then spefically set it to only have the 'loan_status' column in that variable.  To create my "x" variable I did the same thing but instead used a drop method to drop the 'loan_status' column that way the "x" variable will have every column except that one.

  To split them into trianing and testing variables I used the train_test_split function to split the x and y into their own arrays into radnom subsets.

# Create Logistic Regression Model

  To create my logistic regression model I used the LogisticRegression class and created a variable that I could fit into the x and y training data.  After that I used the predict function to test the x variable for my testing array, to find the amount predictions made.

# Credit Risk Analysis Report

  I used the confusion matrix to create the classification report.  I set the confusion_matrix function to use the y_test variable and the predcitions variable I created before off of the x_test.  I then printed the report to show the main classification metrics to be able to analyze my results, in which I answered the question in a markdown file within my code. 
