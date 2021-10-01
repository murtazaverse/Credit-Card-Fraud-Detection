# Credit Card Fraud Detection
A project on techniques with imbalanced classification

## Project Introduction
It is often that the data we retrieve have imbalanced label and we are asked to make classification. These scenarios are troublesome since not only the models we usally use bring poor result, but also the evaluation metric we often used, accuracy, is not adequate for imbalanced data sets due to the impact of the minority class. This project aims to demonstrate some techniques used to combat these situations, such as resampling or cluster before predicting, as well as using PR (Precision-Recall) curve to evaluate model. The approaches for the project are :

   1. Randomly split the dataset into train, validation, and test set.
   2. Do basic EDA and feature engineering.
   3. Predict and evaluate with validation set.
   4. Resample the dataset. 
   5. Train on resampled train set then predict and evaluate with validation set.
   6. Try other different models.
   7. Compare the difference between the predictions and choose the best model.
   8. Find the optimised threshold of the chosen model.
   9. Predict on test set to report final result.
