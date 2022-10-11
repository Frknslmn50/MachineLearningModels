Here we have a dataset which i added to directory (data.csv) that includes the data of some benign and malignant tumors.
Our goal is to estimate if a tumor is benign or malignant.
To do this i inspected the data (null vals , duplicated vals etc.) and reduced the amount of features.
Then i scaled the data and trained 3 different models.
U can see the results in jupyter notebook (BreastCancer_Training.ipynb) and if u don't want to run it on your own i saved RanddomForestRegressor(BreastCancerModel) and LogisticRegression (BreastCancerReg) models, u can download them and with pickle u can import and use them.
