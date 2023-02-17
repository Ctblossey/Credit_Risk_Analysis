# Credit Risk Analysis

## Overview
### The purpose of this exercise was to employ different techniques to train and evaluate models with unbalanced classes. Through different models, we were able to perform different analysis and tested the balanced accuracy scores.

## Results
### The results of the six classification reports are very similar to each other. The main difference is between high risk and low risk overall. Taking a deeper look at the results, low risk has a much higher accuracy than high risk. This makes sense because low risk actions should be easier to predict that those with high risk.

![Resampling Oversampling](https://github.com/Ctblossey/Credit_Risk_Analysis/blob/main/Classification%20Reports/Resampling%20Oversampling.png)
![Resampling SMOTE Oversampling](https://github.com/Ctblossey/Credit_Risk_Analysis/blob/main/Classification%20Reports/Resampling%20SMOTE%20Oversampling.png)
![Resampling Undersampling](https://github.com/Ctblossey/Credit_Risk_Analysis/blob/main/Classification%20Reports/Resampling%20Undersampling.png)
![Resampling Combined Sampling](https://github.com/Ctblossey/Credit_Risk_Analysis/blob/main/Classification%20Reports/Resampling%20Combined%20Sampling.png)
![Ensemble Balanced Random Forest Classifier](https://github.com/Ctblossey/Credit_Risk_Analysis/blob/main/Classification%20Reports/Ensemble%20Balanced%20Random%20Forest%20Classifier.png)
![Ensemble Easy Ensemble AdaBoost Classifier](https://github.com/Ctblossey/Credit_Risk_Analysis/blob/main/Classification%20Reports/Ensemble%20Easy%20Ensemble%20AdaBoost%20Classifier.png)

## Summary
### Overall, the reports provide very good insights. The model is very good for low risk and needs attention/supervision for high risk, having high and low scores, respectively. The model that I would recommend is the Easy Ensemble AdaBoost Classifier model. This is because even though the results are very close to one another, the Ensemble AdaBoost Classifier model has a much higher avg / total when it comes to iba than all of the other models.
