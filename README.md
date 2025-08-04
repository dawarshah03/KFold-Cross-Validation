## KFold-Cross-Validation

In this project, I used machine learning to recognize handwritten digits. I used the digits dataset that comes with sklearn.

First, I used train_test_split to train and test three models: Logistic Regression, SVM, and Random Forest.

Then I wanted to test my models in a better way. So I used KFold cross validation. It splits the data into parts and tests the model on each part. I used a simple function to train the model and get its score, and then I saved all the scores for each model.

After using KFold, I also used StratifiedKFold just to try it out. It makes sure the data is split more evenly.

At the end, I used cross_val_score which does the same thing as KFold but it's easier and automatic. It gave me the scores directly without writing too much code.
