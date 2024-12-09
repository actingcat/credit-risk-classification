# credit-risk-classification
For this assignment, we were tasked with analysing a data set with lending activity from a peer-to-peer lending service company. First, we split the data into training and testing sets by using train_test_split. Then we created a linear regression model, and evaluated the model with a cofusion matrix and classification report. 
# credit risk analysis report:
  The purpose of this report is to determine whether or not the model is a strong method for determining the risk of a loan.
  * In terms of precision, which represents the percentage of correct positive predictions, the healthy loans had a precision of 100%. For the high risk loan, the precision was at 87%, which is still a strong precision score.
  * For recall, which is the ability of the classifier to find all the positive samples, the healthy loans has 99% recall, and unhealthy had 94% recall. 
  * The F1 scores represent the weighted average of precision and recall. The F1 score for the healthy loan was 100%, and 89% for the unhealthy loan.
  * Support represents the number of occurances within a dataset. The healthy loans had a significantly greater number of occurances(over 18k), versus the defaulting loans, that only have about 600 occurances.     This means that the data set is not particularly well balanced. The support numbers would have to be more equal to have a well balanced data set. 
  * Across both loan types, the accuracy score was almost perfect, at 99%.
* Overall, I would recommend that the company use this model to analyze the crediworthiness of its borrowers because it has high percentages in the three categories precision, recall, and F1. 
