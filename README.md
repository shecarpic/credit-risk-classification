# credit-risk-classification
In this Challenge, I used various techniques to train and evaluate a model based on loan risk. I  used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.


Credit Risk Analysis Report

The logistic regression model seems to perform quite well in predicting both the "0" (healthy loan) and "1" (high-risk loan) labels based on the provided metrics (precision, recall, and F1-score).

For the "0" label (healthy loan):
- Precision: 0.99 indicates that among the loans predicted as healthy, 99% were actually healthy.
- Recall: 1.00 (100%) means that the model correctly identified all healthy loans.
- F1-score: 1.00 is a harmonic mean of precision and recall, providing a balanced measure of the model's performance.

For the "1" label (high-risk loan):
- Precision: 0.92 implies that among the loans predicted as high-risk, 92% were actually high-risk.
- Recall: 0.84 indicates that the model captured 84% of the actual high-risk loans.
- F1-score: 0.88 is a combination of precision and recall for the high-risk label.

Overall, the logistic regression model shows high accuracy (99%) and performs well in predicting both healthy and high-risk loans, with particularly strong performance in identifying healthy loans.
