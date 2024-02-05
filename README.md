# credit-risk-classification
Module 20 Challenge

Overview of the analysis (purpose of this analysis):
-To use various technicques to train and evaluate a model for the risk of loans.
-Utilize a dataset containing historical records of lending activities from a peer-to-peer lending services company to construct a predictive model capable of discerning the creditworthiness of borrowers.

Results:
-Accuracy score:  was calculated from the 'y_test', and 'predctions' from the logistic reqresion model created prior.  The accuracy score was the 'balanced_accuracy_score', calculated as about 95%.
-Precision score:  for the 'healthy loan' was 100%, while the 'high-risk loan' was at an 87%.  They both had a 'macro avg' and a 'weighted avg' of 94% and 99%.
-Recall score: had a 100% and a 89% for the 'healthy loan', and 'high-risk loan'.  They both had a 'macro avg' and a 'weighted avg' of 94% and 99%.

Predict a Logistic Regression Model with Resampled Training Data:

Results:
-Accuracy score:  was calculated from the 'y_test', and 'predctions' from the logistic reqresion model created prior.  The accuracy score was the 'balanced_accuracy_score', calculated as about 99%.
-Precision score:  for the 'healthy loan' was 100%, while the 'high-risk loan' was at an 87%.  They both had a 'macro avg' and a 'weighted avg' of 94% and 100%.
-Recall score: had a 100% and a 100% for the 'healthy loan', and 'high-risk loan'.  They both had a 'macro avg' and a 'weighted avg' of 100% and 100%.

Summary:
-Results had improved using the 'Logistic Regression Model with Resampled Training Data'.  I would recommend that model due to the fact of the improved precison  and recall scores.  Not to mentionn the accuracy score improved to 99%.
