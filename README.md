# Car-Insurance-Claim-Prediction-Model
A car insurance claim classifier is a business analytics tool designed to analyze and categorize car insurance claims based on various parameters. It utilizes advanced machine learning techniques to automatically process and understand the contents of claim documents, such as accident reports, repair estimates, and customer statements. The primary use case for a car insurance claim classifier is to streamline and optimize the claims management process.

We can see that there are very less number of cases of policy claims. There is only 0.7% of cases which makes “Class imbalance”. This problem is seen where the no.of observations belonging to one class is significantly lower than those belonging to other classes. The Different Approaches for Handling imbalanced Data are Resampling(apply SMOTE function), Cluster-Based Oversampling.
We have a package named “imblearn” which is mostly preferred for solving the Class imbalance problem.

We use Hyperparameter tuning for maximize the performance of the model using arranging several parameters and attributes for the model.To perform Hyperparameter tuning we have two methods which are most widely used:

1: RandomizedSearchCV

2: GridsearchCV

Now I have used Grid search CV for the Logistic Regression.

The csv file contains 58592 rows of data and 44 columns reprenting the features of the data set. Encoding of the categorical variables is important to make the model understand the dataset more comfortable.

This project had 5 steps :

1: Importing Libraries

2: Dataset Analysis

3: Preprocessing & Feature EDA

4: Splitting the dataset

5: Classification model selection and training
