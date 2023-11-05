# credit-risk-classification-Unit-20

An Overview Of The Analysis: The purpose of the analysis was to create a Supervised Learning program which is used to predict if a borrower has a healthy loan profile (value of 0) or a high risk profile (value of 1).

From the data collected there were 75036 that had good credit scores and 2500 that did not. Using the loan status column to determine if its a safe to lend a loan out to that customer.
After spilting the data into test and trainning data than making a liner regression. The results showed a 99% accuary towards the machine learning.
It was done again by Randomizing the data and it still came with a 99% accaury towards determing if the customer is a high risk or not.

The Results were as follows:
For the first model
              
               precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   
   macro avg       0.92      0.95      0.94     19384

weighted avg       0.99      0.99      0.99     19384

For the second model
 
                precision   recall    f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
  
   macro avg       0.92      0.99      0.95     19384

weighted avg       0.99      0.99      0.99     19384


A Summary: After running each model,the Model 2 performs slightly better. The results above show a very close comparison between each model.  Therefore, I would recommend to use Model 2 as it better predicting than Model 1.

