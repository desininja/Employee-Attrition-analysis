# HR-analytics
To know the main reasons of attrition of employees.

File data_dictionary contains all the feature information, explaining the feature values and impact.
Attrition is the target column. Attrition means employees who left the organization. 
We need to find which factors/features of the Data is related to attrition of employees.

The data is imbalanced.
Main problem with imbalance is that the model does not understand the minority class well and tries to categorize them as the majority class.
For example: Suppose we have 98 pictures of dogs and only 2 pictures of cat, even if model does not categorize those cat correctly the error will be only 2%,
it will show the accuracy at 98%. Hence for imbalanced data accuracy is not a best measure for model performance. 
We need to check other things like precision, F1 score, recall to get better idea of working of model.

How can we get rid of this imbalance problem?

So there are many techniques to address this issue.

1) Undersampling: Reduce the major class of the data
2) Oversampling: Increase the minority class of the data
3) SMOTE: Full form Synthetic Minority Oversampling Technique, it is used to make sythetic data to overcome the imbalance.

There are many other techniques.

I have used undersampling and SMOTE and compared there result.

See the code file(HR analytics.ipynb) and commented section for better understanding.

At the end i have compared the coefficients of the relevant features to get features that have good relation with attrition.
