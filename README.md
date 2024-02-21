# Classification Algorithms with Python

## Introduction: 
This notebook explores historical data of a loans dataset that can be explored as a classification problem.
Use data pre-processing techniques and convert or normalize values to create insightful multidimentional views with data visualization. The categorical target variable, `loan_status` is classified into categories `PAIDOFF` or `COLLECTION`. 


## Parameter of Functions
normalize of .value_counts()


## The Plan
1. Pre-process data to a state it can be effectively analyzed
   * convert
   * impute
2. Explore trends in categories
   * try binning
   * try changing features
3. Establish Thresholds
   * try creating new fields to categorize variables for more information
4. Create numerical veriables from categorical to create another point of view
5. Create groups of school group with .groupby()
6. One Hot Encoding to convert categorical to binary variables to differentiate school groups
7. Standardization/Normalize Data (AFTER train test split)
   * mean = 0
   * unit variance = 0
8. Classification
   * 1. TRAINING set **to** build model
   * 2. TEST set **to** report accuracy of the model

9. Classification algorithmss: KNN, decision tree, SVM, logistic regression
    * KNN - fiind the best k



accuracy evaluation methods - to find the best algorithm for the data set
