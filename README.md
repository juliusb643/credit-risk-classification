# credit-risk-classification

Module 20

The purpose of this analysis is to see how well the models can perform when asked to predict certain values. 

                   precision recall  f1-score   support

           0       1.00      1.00      1.00     18762
           1       0.87      0.92      0.89       622

    accuracy                           0.99     19384
   macro avg       0.93      0.96      0.94     19384
weighted avg       0.99      0.99      0.99     19384


I would recommend against using this model because of the dropoff in precision and recall of the high-risk loans. While the weighted averages look good, this is skewed by an almost perfect dataset. There are only 622 instances of category 1's, or high-risk loans, while there are 18,762 healthy loans. The model is great at predicting healthy loans, and that is what is boosting the score. However, if the instances were closer in number, I believe the numbers would be more off and not accurate. 
