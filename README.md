# Credit_Risk_Analysis

### Overview of the Analysis

The purpose of this analysis is to understand how machine learning is used to analize credit risk in the lending world. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. We will be employing different techniques to train and evaluate models with unbalanced classes. We will use RandomOverSampler and SMOTE algorithums  to oversample the data, the ClusterCentroids algorithum to undersample the data, and then the combination of the two to using the SMOTEENN algorithum. Then we will compare the two machine learnings that reduce bias to predict credit risk. To do that we will be using the BalancedRandomForestClassifier and EasyEnsembleClassifier algorithums.

### Results

Below we are going to represent each algorithum method to see the risk variances for each.

#### Naive Random Oversampling
![Naive_Oversampling](https://user-images.githubusercontent.com/106560752/195467274-19c5f9c8-48e6-4cb0-bc2e-b3ab712eed0e.png)
* The balancing accuracy for this is 0.65/100 which isn't very accurate.
* The precision for highrisk is really low at 0.01 while the precision for lowrisk is at 1.00 which is perfect.
* 

#### SMOTE Oversampling
![SMOTE_Oversampling](https://user-images.githubusercontent.com/106560752/195467324-e35e6efe-01a1-41bf-938f-696685f1fb87.png)


#### Undersampling
![Clustered_Centoids](https://user-images.githubusercontent.com/106560752/195467422-b68d2b30-ecd3-49d2-ba1c-def154433a18.png)


#### Over/Under Combination
![Over_Under](https://user-images.githubusercontent.com/106560752/195467366-52ad7c2e-6716-4ab5-8879-b43d20da27a6.png)


#### Balanced Random Forest Classifier
![Balance_Random_Forcaster](https://user-images.githubusercontent.com/106560752/195467483-0bab6827-de56-44d0-8014-ce90c0424aee.png)


#### Easy Ensemble AdaBoost Classifier
![Easy_Ensemble_AdaBoost_Classifier](https://user-images.githubusercontent.com/106560752/195467523-83fb7965-946c-4db1-be98-723d2b8e36ec.png)


