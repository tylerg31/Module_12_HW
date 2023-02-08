# Module_12_HW
Module 12 Challenge 

In this analysis we created a logistic regression model to classify and then predict if loans should be accepted or not. To complete this analysis
we began by taking prior loan data and training the model. We used 75% of the data as training data and the rest as testing data. Our model looked
at several data points such as loan amount, interest rates, and borrower income to make a determination about the approval or disproval of the loan.

For the first trial of the data we used the raw data without adjustments. Our model produced the following scores for detecting bad loans:
Precision: .85
Recall: .91
F1 score: .88

For the next trial of the data we oversampled the minority class of defaulted loans. This class was underrepresented and could distort the model
by encouraging it to approve all loans since defaults are more rare than successful loans. 
In the second run our model produced the following scores:
Precision: .84
Recall: .99
F1 score. .91

We can conclude that our model using the resampled data produced better results. We had a slight loss of precision but the model had fewer false
postives and only slightly more false negatives. 

