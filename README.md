# Credit Risk Classification Analysis

## Overview of the Analysis

The analysis compared two machine learning models that were used to predict whether a loan is healthy or high-risk. Both models had an accuracy of 0.99. Model 1 had slightly higher precision for label 1 (high-risk loan) while Model 2 had slightly higher recall for label 1 (high-risk loan). The best model depends on whether it is more important to predict label 1 with higher precision or higher recall.

## Results

* Machine Learning Model 1:
  * The model has an accuracy of 0.99
  * For label 0 (healthy loan), the model has a precision of 1.00 and a recall of 0.99
  * For label 1 (high-risk loan), the model has a precision of 0.85 and a recall of 0.91


* Machine Learning Model 2:
  * The model has an accuracy of 0.99
  * For label 0 (healthy loan), the model has a precision of 1.00 and a recall of 0.99
  * For label 1 (high-risk loan), the model has a precision of 0.84 and a recall of 0.99

## Summary

In the context of credit risk analysis for a bank, it is important to consider the potential consequences of false positives and false negatives. A false positive in this case would mean that a healthy loan is incorrectly classified as high-risk, while a false negative would mean that a high-risk loan is incorrectly classified as healthy.

If the cost of a false negative is higher than the cost of a false positive (i.e. if the bank would suffer more from granting a high-risk loan than from denying a healthy loan), then Model 2, with its higher recall for label 1 (high-risk loan), may be the better choice. This model correctly identifies almost all high-risk loans, minimizing the risk of granting a high-risk loan.

On the other hand, if the cost of a false positive is higher than the cost of a false negative (i.e. if the bank would suffer more from denying a healthy loan than from granting a high-risk loan), then Model 1, with its higher precision for label 1 (high-risk loan), may be the better choice. This model has fewer false positives, minimizing the risk of denying a healthy loan.

Ultimately, the best model depends on the specific needs and priorities of the bank. It is important to carefully evaluate the potential costs and benefits before making a decision.