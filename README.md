# Credit-Card-Fraud-Detection

 Credit Fraud Detector

Note: There are still aspects of this notebook which are subject to changes.


Introduction
In this notebook we will use various predictive models to see how accurate they are in detecting whether a transaction is a regular payment or a fraud. The features are scaled and the names of the features are not shown due to data privacy. 

Our Goals:

    1. Understand the distribution of the "little" data that was provided to us.
    2. Create a 50/50 sub-dataframe ratio of "Fraud" and "Non-Fraud" transactions.
    3. Determine the Classifiers we are going to use and decide which one has a higher accuracy.
    4. Create a Neural Network and compare the accuracy to our best classifier.
    

Outline:
1. Understanding our data
  1.1 Gather Sense of our data

2. Preprocessing
  2.1 Scaling and Distributing
  2.2 Splitting the Data

3. Random UnderSampling and Oversampling
  3.1 Distributing and Correlating
  3.2 Anomaly Detection
  3.3 Dimensionality Reduction and Clustering (t-SNE)
  3.4 Classifiers
  3.5 A Deeper Look into Logistic Regression
  3.6 Oversampling with SMOTE

4. Testing
  4.1 Testing with Logistic Regression
  4.2 Neural Networks Testing (Undersampling vs Oversampling)
