# Credit_Risk_Analysis

### Overview
We are helping Jill with a new project in the credit card risk department. We are using imbalanced-learn along with scikit-learn libraries to get the job done. By using the dataset we were provided from LendingClub, we will oversample the data using the RandomOverSampler and SMOTE algorithms. We will then undersample the data with ClusterCentroids, use a combinational approach of over and undersampling using SMOTEENN, and compare the two machine learning models using BalancedRandomForestClassifier and EasyEnsembleClassifier to predict the credit risk. 

### Results

#### Naive Random Oversampling
![This is an image](https://github.com/clarosjorge21/Credit_Risk_Analysis/blob/96a04f4112a279b0e2b1922e44678b63e84c6d90/Images/Naive.PNG)
* The balanced accuracy score is: 0.6293939430565123
* The precision score is: low for High-risk loans and high for Low-risk loans
* The recall is: High/Low = 0.57/0.68

#### SMOTE Oversampling
![This is an image](https://github.com/clarosjorge21/Credit_Risk_Analysis/blob/96a04f4112a279b0e2b1922e44678b63e84c6d90/Images/Smote_Over.PNG)
* The balanced accuracy score is:0.6277008271188627
* The precision score is: low for High-risk loans and high for Low-risk loans
* The recall score is: 0.62/0.63

#### Undersampling
![This is an image](https://github.com/clarosjorge21/Credit_Risk_Analysis/blob/96a04f4112a279b0e2b1922e44678b63e84c6d90/Images/Under.PNG)
* The balanced accuracy score is: 0.6277008271188627
* The precision score is: low for High-risk loans and high for Low-risk loans
* The recall score is: 0.57/0.68

#### Combination Under-Over Sampling
![This is an image](https://github.com/clarosjorge21/Credit_Risk_Analysis/blob/96a04f4112a279b0e2b1922e44678b63e84c6d90/Images/Over_Under.PNG)
* The balanced accuracy score is: 0.6411460410698961
* The precision score is:low for High-risk loans and high for Low-risk loans
* The recall score is: 0.70/0.58

#### Balanced Random Forest Classifier
![This is an image](https://github.com/clarosjorge21/Credit_Risk_Analysis/blob/96a04f4112a279b0e2b1922e44678b63e84c6d90/Images/Random_Forest.PNG)
* The balanced accuracy score is: 0.7877672625306695
* The precision score is: low for High-risk loans and high for Low-risk loans
* The recall score is: 0.67/0.91

#### Easy Ensemble AdaBoost Classifier
![This is an image](https://github.com/clarosjorge21/Credit_Risk_Analysis/blob/96a04f4112a279b0e2b1922e44678b63e84c6d90/Images/EE_Adaboost.PNG)
* The balanced accuracy score is: 0.925427358175101
* The precision score is:low for High-risk loans and high for Low-risk loans
* The recall score is: 0.91/0.94

### Summary
As you can see above, using different machine learning models we are able to see different types of balanced accuracies, precisions and recall numbers. Overall, I think in this situation we are going for a high balanced accuracy score. Using the Easy Ensemble AdaBoost Classifier we are able to get the highest balanced accuracy score at 93% compared to the rest the next highest is 79%. The precision between all the models are almost all the same. 
