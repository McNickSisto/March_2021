### Project: Tabular Playground Series - Mar 2021 - Predictor in production

### Description: This project aims to predict a binary target. The challenge is released once a month by Kaggle and open for everyone. 
As training data there is a total of 300,000 observations with 30 features. 
11 features are continuous values (standardized) and 19 features are categorical. 
Categorical features need to be OHE because they are in the form of STRINGS. 
The target of 0 and 1 is also unbalanced, leaning towards skewed to 1. To balance the data the oversampling techinque of SMOTE is used. 
As a final estimator the XGBClassifier is chosen.

### Data Source: https://www.kaggle.com/c/tabular-playground-series-mar-2021/data

### Scorer: Area under the Curve (AUC)
### Type of analysis: Various models test


Startup the project
Download the provided data from Kaggle. Or use the direct download CLI command kaggle competitions download -c tabular-playground-series-mar-2021

Go to the Challenge on Kaggle: Link

upload the test.csv click Predict & Download

You will have the predictions ready for submission in your download folder

### Summary
The overall Kaggle score for this predictor is 0.86792
