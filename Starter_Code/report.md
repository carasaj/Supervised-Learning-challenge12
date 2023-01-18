##  Analysis

* In this challenge, machine learning is used to train a model by evaluating lending activity data. The goal is to identify the creditworthiness of a borrower.
* The data provided (features) includes loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt. The target was their loan status.
* Using the value_counts method identified how many borrowers were marked positive or negative.
* The feature and target data was split in to training and testing sets. The training sets were used to fit the model and then generate predictions to be weighed against the testing sets for accuracy.
* The methods used were Logistic Regression, for the analysis itselff, along with Random OverSampling, which was used to balance the data.


## Results

* Machine Learning Model 1:
  * Accuracy was at about 95%, whereas average precision and recall were both at 99%. The postitive and negative precision/recall values had a variance of 15 and 8, respectively.


* Machine Learning Model 2:
  * Accuracy was at about 99%, whereas average precision and recall were both at 99%. The postitive and negative precision/recall values had a variance of 16 and 0, respectively.


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* The random oversampling method performed better as it had a higher accuracy score while retaining consistent or better precision and recall.
* Depending on the goal of the analysis, it could be more accurate to use the original data or integrate another data transforming step. This depends on any weighting that may favor positive or negative results.
* I recommend using the random oversampled data with logistic regression.

