# Data-Mining-and-Machine-Learning
# PERFORMANCE OF DIFFERENT MACHINE LEARNING METHODS IN THREE DATASETS


![N|Solid](https://www.nag.com/sites/default/files/styles/banner/public/2020-08/machine-learning.jpeg?itok=4WFu3LAS)

This project describes that how three different datasets such as chess game, used cars and a job change of Data Scientists are performed using various machine learning algorithms.The machine learning techniques used in the three datasets are Random forest, Decision tree, Xgbboost (eXtreme Gradient Boosting), and KNN (K-Nearest Neighbours). It explains the machine learning models by training the model with datasets which are cleaned, processed, transformed, analyzed and best features are selected to fit the model. For different approaches, two classification problems and one regression problem are taken to solve. The Dataset 1- chess game is a classification problem, which has multi class that which player will win the game, either White, Black or the game is Draw. The Dataset 2- Used Cars is a regression problem, in that price of the used cars will be predicted by using the relevant features of the cars such as manufacturer, color, condition, year of manufacturing etc., The Dataset 3- A job change of Data Scientists is also a classification problem, which is about the candidates who applied for Data Scientist position. The prediction will be whether the candidate leaves the job or not, after attending the training in the company.

Research Questions

1. Can we predict the winner of the game? (Classification Problem)
2. Can we forecast the price of the used car? (Regression Problem)
3. Can we predict the candidate who change into new employment after the training? (Classification Problem)



## METHODOLOGY

The process of finding helpful information from a data collection is called as Knowledge Discovery in Databases (KDD). This strategy utilizes data preprocessing and selection, data cleansing, integrating previous understanding of data sets, and evaluating precise prediction from measured data. The steps associated with the process of KDD are,

-The data is extracted from kaggle website and dependent variable is selected.

-Data Cleaning is cleaning the null values either by removing it or using imputation to fill it. The outliers are checked for numerical variables and it is handled by 
removing it.

-The data is studied and understood the type of data and the statistical information about the data to perform good analysis to evaluate the result.

## DATA SELECTION
The Three Dataset that we selected are from three different fields such as 
1.Chess game
2.Used Cars
3.A Job change of Data Scientist

##  DATA PRE-PROCESSING
Dataset-1: Chess game
The selected feature variables from dataset are rated, victory status, white rating, black rating, and opening ply, these are used to predict the target variable-winner.

Dataset-2: Used Cars
1.Filter Method
2.Backward Elimination (Wrapper Method)

Dataset-3: A Job change of Data Scientist
Missing values, Label encoding, and Correlation

## EVALUATION AND RESULTS
#### DATASET 1: CHESS GAME
##### Model 1
Random Forest

The Random Forest Classifier model has the accuracy of 0.6612662013958126.The F1 score is 0.75, which is a good score that it means the model is fitted well.

##### Model 2
XGB BOOST CLASSIFIER

The XGB Boost Classifier model has the accuracy of 0.665.The F1 score is 0.76, which is a good score that it means the model is fitted well.

#### DATASET 2: Used Cars
##### Model 1
Decision Tree

The R square value is 0.49754096786136004

##### Model 2
Decision Tree Regressor

The Rsquare value is 0.5092248866079689

#### DATASET 3: A Job change of Data Scientist
##### Model 1
XGB Boost

The Rsquare value is 0.7785507246376812.The F1 Score is 0.73, which is good score for the 
model.

##### Model 2
Random Forest

The R square value is 0.7794202898550725. The F1 Score is 0.72, which is good score for the model.

##### Model 3
KNN MODEL

The R square value is 0.7892753623188405.The F1 score is 0.76, which is a better score compared to the two models.


The Data are extracted from Kaggle, Pre-processed and transforming the data to interpret data mining and evaluate the best results from fitting various models in machine learning techniques. In Dataset1, Both Random Forest, XGB Boost Classifier proved to be the best model with accuracy of 66% and 66% respectively and F1 score are 0.75 and 0.76 respectively, for predicting which player would win. In Dataset 2, comparing to Random Forest, Random Forest regressor proved to be the best model with R square 0.50, for predicting the price of used cars. In Dataset 3, Compared to XGB Boost and Random Forest, K-Nearest Neighbour algorithm has proved to be the best fitted model with accuracy of 78% and F1 score 0.76. For Future works, the advanced techniques will be used to proceed with best and efficient evaluations and results.

