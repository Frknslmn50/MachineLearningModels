We have a dataset of patients some of whom have diabetes. Given a patient's Age , Pregnancies , Glucose lvl ,... we are trying to estimate if that patient has diabetes.
First I inspected if data has null values or outliers.I plotted all columns as a boxplot and looked for the outliers. 
It didn't have any null vals but I needed to suppress outliers and for that i used winsorize from scipy.stats.mstats.
At the end i used LogisticRegression , RandomForestClassifier , XGBClassifier , CatBoostClassifier to model the data and u can see the results from jupyter notebook.
