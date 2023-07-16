# Predicting-credit-card-approvals
It is a supervised learning task of predicting whether a credit card application has to be approved or rejected.It is done based on 15 feature variables such as income, credit score, prior default etc.
First the data is loaded as a pandas dataframe then it is preprossed (Null values replaced, test train split and data scaling)
Then in the modelling phase, lazypredict module is used to implement various traditional algorithms and also a neural network model is implemented
At last the performance of the models are measured
Required python modules: pandas, numpy, seaborn, matplotlib, sklearn, lazypredict, tensorflow, scikeras
