# Fraud Detection in Credit Card Applications of a Bank

This application detects potential frauds within the credit card applications of a bank. It generates an explicit list of
customers of the bank who potentially cheated. This deep learning model identifies some patterns in a high dimensional dataset
full of non linear relationships and one of these will be the potential frauds.

## Information about the Dataset
The name of the dataset used here is 'Credit_Card_Applications.csv' and it is taken from the UCI Machine Learning website.<br/>
Link : http://archive.ics.uci.edu/ml/datasets/statlog+(australian+credit+approval)<br/>
This file concerns credit card applications. All attribute names and values have been changed to meaningless symbols to protect confidentiality of the data.This dataset is interesting because there is a good mix of attributes -- continuous, nominal with small numbers of values, and nominal with larger numbers of values. There are also a few missing values. 

## Attribute Information
There are 6 numerical and 8 categorical attributes. The labels have been changed for the convenience of the statistical algorithms. For example, attribute 4 originally had 3 labels p,g,gg and these have been changed to labels 1,2,3.
<br/>
A1: 0,1 CATEGORICAL (formerly: a,b)<br/>
A2: continuous.<br/>
A3: continuous.<br/>
A4: 1,2,3 CATEGORICAL (formerly: p,g,gg)<br/>
A5: 1, 2,3,4,5, 6,7,8,9,10,11,12,13,14 CATEGORICAL (formerly: ff,d,i,k,j,aa,m,c,w, e, q, r,cc, x)<br/>
A6: 1, 2,3, 4,5,6,7,8,9 CATEGORICAL (formerly: ff,dd,j,bb,v,n,o,h,z)<br/>
A7: continuous.<br/>
A8: 1, 0 CATEGORICAL (formerly: t, f)<br/>
A9: 1, 0 CATEGORICAL (formerly: t, f)<br/>
A10: continuous.<br/>
A11: 1, 0 CATEGORICAL (formerly t, f)<br/>
A12: 1, 2, 3 CATEGORICAL (formerly: s, g, p)<br/>
A13: continuous.<br/>
A14: continuous.<br/>
A15: 1,2 class attribute (formerly: +,-) <br/>

## Deep learning model used
This application is implemented in two parts.The first part contains of Self Organising Maps , which is an unsupervised deep learning model.
The second part contains the implementation of Artificial Neural Network using Keras Library which uses tensorflow backend.