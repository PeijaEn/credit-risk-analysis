# credit-risk-analysis

(Could not add csv file, was too big and laptop wouldn't git push.)


### Overview of the Loan Prediction Risk Analysis

The purpose of this analysis was to create multiple models to preform different types of machine learning. Out of the data provided, I was given a very unbalanced set:

- low-risk: 68470
- high-risk: 347

### Result


Naive Random Oversampling
![image]()

SMOTE Oversampling
![image]()

Undersampling
![image]()

Combination Over-Under Sampling
![image]()

Balanced Random Forest Cassifier
![image]()

Easy Ensemble AdaBoost Classifier
![image]()



### Summary

The Easy Ensemble AdaBoost Classifier had the highest overall accuracy out of all my models. This may have been due to the data being so unbalance, you can see this within its F-score for high risk prediciton being 0.16 only, nowhere near .9. I would not advise these models to be used in actual analysis but if I was forced to choose one it would be the Easy Ensemble AdaBoost Classifier.
