# Credit_Risk_Analysis
## Overview of Analysis
The purpose of this project is to analyse a credit risk dataset to then create various Machine Learning models to see which model will be best to be able to predict giving approving a loan based on their risk profile or denying them using various features of the dataset.

## Results
There were six models used for this analysis. The results for these models are:

* Random Oversampling
<img width="845" alt="Random_OverSampling" src="https://user-images.githubusercontent.com/85206793/174498191-ef539202-e70a-4556-8b4d-a1091abf0eb4.png">

  With the oversampling model, the balanced accuracy score of the model is slightly above the half way which is about 63%.

  The precision and sensitivity scores were at 1% for high risk, 100% for low risk and 59% for high risk and 68% for low risk respectively.

* Synthetic Minority Oversampling Technique (SMOTE)
<img width="755" alt="SMOTE" src="https://user-images.githubusercontent.com/85206793/174498247-ded8e234-7cf4-44fd-ade2-ad68d59603c6.png">

  With the SMOTE model, the balanced accuracy score of the model is also is about 63%.

  The precision and sensitivity scores were at 1% for high risk, 100% for low risk and 44% for high risk and 57% for low risk respectively.

* Cluster Centroids
<img width="755" alt="ClusterCentroids" src="https://user-images.githubusercontent.com/85206793/174498267-9f4b0f0e-9047-4187-bf58-9832283f53a3.png">

  For the Cluster Centroids model, the balanced accuracy score of the model is exactly at the 50% mark.

  The precision and sensitivity scores were at 1% for high risk, 100% for low risk and 61% for high risk and 64% for low risk respectively.

* SMOTE and Edited Nearest Neighbors (ENN) (SMOTEENN)
<img width="755" alt="SMOTEENN" src="https://user-images.githubusercontent.com/85206793/174498308-09cf51b7-19a1-4c3d-a2f4-eb1cf60b0ca5.png">

  The SMOTEENN model has a balanced accuracy score of 63% also.

  The precision and sensitivity scores were at 1% for high risk, 100% for low risk and 71% for high risk and 54% for low risk respectively.

* Easy Ensemble
<img width="755" alt="Easy_Ensemble" src="https://user-images.githubusercontent.com/85206793/174498314-56a4610e-b4a6-4164-a306-a98d9934ef8f.png">

  The Easy Ensemble model on the other hand has a balanced accuracy score of 93%.

  The precision and sensitivity scores were at 7% for high risk, 100% for low risk and 91% for high risk and 94% for low risk respectively.
  
 ## Summary
 After executing all these models, it can be seen clearly that some models are not useful to clearly determine the risk profile of an applicant.
 The accuracy score of the models tells us that the models are having a hard time predicting who to approve or deny for the loan. In a case like giving out
 a loan, precision is key here because the model has to be able to filter the good and bad applicants and not blanket the whole pool and deny people who
 deserve the loan.
 
 ## Recommmendation
 Between all the models, the Easy Ensemble model seems more likely to be used to process these applications. This is because out of the six models, that is
 the only one with an accurancy score of 93% but it is not recommended. 
 This is because it has an precision of just 7% to detect the high risk applicants.
 One way this can be improved is to remove the features that have no importance in the model. This creates a more definitive training and testing in order
 to have a higher precision score to be able to the detect the high risk applicants and not just the low risk ones..
