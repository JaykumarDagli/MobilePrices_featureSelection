# MobilePrices_featureSelection

This is a mini project to understand feature selection technique. We have a 'train.csv' file with 2000 records that contains parameters that can impact the price of a mobile phone. For eg: RAM, battery etc and the response variable is 'price range'.

We have used logistic regression classifier to check the accuracy and then used 'selectkbest' to find the most important features.

Also, we have tried Random forest and 'feature_importance_' parameter of the RF classifier to see if the accuracy improves if we used lesser number of high importance features. The accuracy was improved from 0.88 to 0.91
