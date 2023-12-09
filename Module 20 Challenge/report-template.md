# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

For Healthy Loans:
Precision: 99.7%
Recall: 99.5%

For High-Risk Loans:
Precision: 84.7%
Recall: 91.0%

Overall Accuracy: 99.2%


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

For Healthy Loans:
Precision: 100%
Recall: 99.4%

For High-Risk Loans:
Precision: 84.1%
Recall: 99.04%

Overall Accuracy: 99.2%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

Both models have exhibited commendable overall accuracy, but Model 2, trained on oversampled data, particularly stands out due to its improved recall for the high-risk class in comparison to Model 1. The critical decision between the two models largely depends on specific objectives. If the primary goal is the precise identification of high-risk loans, the superior recall of Model 2 for the high-risk class makes it a more attractive option.

When making this decision, careful consideration of business implications becomes pivotal. Is the priority to accurately pinpoint high-risk loans, even if it results in more false positives? Alternatively, does achieving a balanced performance take precedence? The decision-making process should involve a nuanced assessment of precision and recall, aligning with the unique business context and priorities.

Choosing Model 2 could be a prudent move, particularly if a more cautious approach is favored to minimize false negatives. This decision should be guided by a strategic evaluation of the trade-offs between precision and recall, emphasizing the relevance of the business objectives in the context of the lending landscape.





