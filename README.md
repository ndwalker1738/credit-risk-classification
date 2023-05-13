# credit-risk-classification

# Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1: Original Data
  * Description of Model 1 Accuracy, Precision, and Recall scores.
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18754
           1       0.84      0.90      0.87       630

    accuracy                           0.99     19384
   macro avg       0.92      0.94      0.93     19384
weighted avg       0.99      0.99      0.99     19384

Balanced Accuracy Score: 0.944819644824977

* Machine Learning Model 2: Randomly Oversampled Data
  * Description of Model 2 Accuracy, Precision, and Recall scores.
            precision    recall  f1-score   support

       0       1.00      0.99      1.00     18754
       1       0.84      0.99      0.91       630

    accuracy                           0.99     19384
    macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384

Balanced Accuracy Score: 0.992965733447764

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
1. Which one seems to perform best? How do you know it performs best? 
* Random oversampled data worked best due to improving the balance of scores and yielding a higher balanced accuracy. 
* We should cut down on false positives and false negatives . Accuracy is always key. I prefer the ROS data due to higher balanced accuracy. 
