# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
 *The purpose of this analysis is to accurately forecast how many loans will be healty and how many will default.
* Explain what financial information the data was on, and what you needed to predict.
   We need to predict if a client will default on their loan payments given their data. 
     * The rate
     * Amount 
     * Income 
     * Debt to income
     * Derogatory marks
     * Total debt 
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
     * We are trying to predict the loan status, either healthy or default.
* Describe the stages of the machine learning process you went through as part of this analysis.
     * Cleaning the data 
     * Separating the target from the rest of the variables
     * Train and test the data by splitting it
     * Choose a model to train the data
     * Fit the data 
     * Check the answers for accuracy
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
 *We used it to oversample the data. since the loans at risk are very minimal compared to the healthy loans, the model with the original data may treat all loans as healthy and still have high accuracy. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
    * Accuracy 95.2%
    * Precision 85%
    * Recall 91%


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
      * Accuracy 99.4%
      * Precision 84%
      * Recall 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
 * The second model performed better, because the recall increased from 91% to 99% therefore decreasing the liabily of default loans
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
 * We are trying t predict the amount of loans that would default, therefore trying to be more accurate on predicting the "1"'s is more important. 

