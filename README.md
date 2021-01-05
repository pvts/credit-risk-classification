# Credit Risk Classification

Our goal is to use Machine Learning techniques to solve the above task. Financial institutions are nowadays risk-averse and they need to estimate the risk involved when giving out credit to their customers. In addition, they need to be in the position to justify why they have either accepted or rejected a credit application due to regulatory requirements. It is important to note that our overall approach is by no means exhaustive.

Initially, we use visualization techniques to identify any patterns within the data. Subsequently, the data is further cleaned and as there are missing values in some of the columns, we use imputation to deal with them.

For this problem, we test and compare the performance of the following classifiers;
- Logistic regression
- Decision Tree
- XGBoost

The evaluation metric used is recall and we find the latter classifier to perform better than the other ones. The dataset is imbalanced and to combat this we use the oversampling technique by artifically increasing the minority class using SMOTE. Moreover, we use gridsearch to find the best parameters. After extensive hyper-parameter tuning the model achieves 88% test accuracy. All of the findings can be found within the Jupyter Notebook.

The dataset has been obtained from https://www.kaggle.com/uciml/german-credit. The original source, where the dataset has been obtained from, can be found at https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29
