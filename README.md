# Credit_Risk_Analysis
## Overview of Analysis
The purpose of this project is to analyse a credit card dataset to then create various Machine Learning models to see which model will be best to be able to predict giving approving a credit card application or denying them using various features of the dataset.

## Results
There were six models used for this analysis. The results for these models are:

* Random Oversampling
<img width="845" alt="Random_OverSampling" src="https://user-images.githubusercontent.com/85206793/174498191-ef539202-e70a-4556-8b4d-a1091abf0eb4.png">

With the oversampling model, the balanced score of the model is slightly above the half way which is about 63%
The precision and sensitivity scores were at 1% for high risk, 100% for low risk and 59% for high risk and 68% for low risk respectively.
* Synthetic Minority Oversampling Technique (SMOTE)
<img width="755" alt="SMOTE" src="https://user-images.githubusercontent.com/85206793/174498247-ded8e234-7cf4-44fd-ade2-ad68d59603c6.png">

With the SMOTE model, the balanced score of the model is also is about 63%
The precision and sensitivity scores were at 1% for high risk, 100% for low risk and 44% for high risk and 57% for low risk respectively.
* Cluster Centroids
<img width="755" alt="ClusterCentroids" src="https://user-images.githubusercontent.com/85206793/174498267-9f4b0f0e-9047-4187-bf58-9832283f53a3.png">


For the Cluster Centroids model, the balanced score of the model is exactly at the 50% mark
The precision and sensitivity scores were at 1% for high risk, 100% for low risk and 61% for high risk and 64% for low risk respectively.
* SMOTE and Edited Nearest Neighbors (ENN) (SMOTEENN)
<img width="755" alt="SMOTEENN" src="https://user-images.githubusercontent.com/85206793/174498308-09cf51b7-19a1-4c3d-a2f4-eb1cf60b0ca5.png">
* Easy Ensemble
<img width="755" alt="Easy_Ensemble" src="https://user-images.githubusercontent.com/85206793/174498314-56a4610e-b4a6-4164-a306-a98d9934ef8f.png">
