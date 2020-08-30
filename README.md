# Predict-the-profit-of-companies
#### Predict the profit of companies using Linear Regression.


- Trained the  Model using the Linear Regresion. then predict the test set.
- Applied Feature Selection Technique(backward elimination) to find out the best Feature in the  given dataset.
- then  select the most significant feature in give dataset and trained the model using  '__Most Significant__' feature.
- then predict the test set.
- finally visualize the data.

 ### Result:
 
| Sr.           | Simple Linear Regression     | Score(in % )|
|---------------|:----------------------------:| ---------:  |
| 1.            | Train set result             |   0.95      |
| 2.            | Test set result              |   0.87      |

- in above result  the train & test accuracy are different which shows the overfitting in train set. we reduce this problem by selecting  best feature.

| Sr.           | After Backward Elimination   | Score(in % )|
|---------------|:----------------------------:| ---------:  |
| 1.            | Train set result             |   0.94      |
| 2.            | Test set result              |   0.94      |
