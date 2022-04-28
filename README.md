# Credit_Risk_Analysis
## Project Overview
Use different types of supervised machine learning model to preform analysis of credit risk prediction. In this project, we need to split our datas into two different dataset: training and testing. By using 6 different methods to get the accuracy score, confusion matries and classification report for prediction.

Methods we used in this project: 

- Naive Random Oversampling
- SMOTE Oversampling
- Cluster Centroid Undersampling
- SMOTEENN Sampling
- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifier

## Result
See the detail analysis provided alonUg with balanced accuracy scores, precision and recall scores.  

### Naive Random Oversampling
- Accuracy Score: 64%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 61%
- Recall Low Risk: 67%

<img width="640" alt="Navie_random_oversampling" src="https://user-images.githubusercontent.com/94089680/164953677-65bcfe8f-bac4-42a2-85f9-8e04e831a99d.png">



### SMOTE Oversampling

- Accuracy Score: 62.3%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 59%
- Recall Low Risk: 66%

<img width="644" alt="SMOTE_oversampling" src="https://user-images.githubusercontent.com/94089680/164953690-b5e59d4b-4249-49e9-aa03-cb84e795029b.png">


### Cluster Centroid Undersampling

- Accuracy Score: 51.03%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 59%
- Recall Low Risk: 43%

<img width="698" alt="Undersampling" src="https://user-images.githubusercontent.com/94089680/164953993-18f5ba06-00b0-4a78-8472-cae1e54ea217.png">



### SMOTEENN Sampling

- Accuracy Score: 65.48%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 74%
- Recall Low Risk: 57%

<img width="890" alt="SOMTEENN_Sampling" src="https://user-images.githubusercontent.com/94089680/165798169-1d5ff76e-8da7-4520-be22-da20cf0e3a27.png">



### Balanced Random Forest Classifier

- Accuracy Score: 78.78%
- Precision High Risk: 4%
- Precision Low Risk: 100%
- Recall High Risk: 67%
- Recall Low Risk: 91%

![Balanced_Random_Forest_Classifier](https://user-images.githubusercontent.com/94089680/164948100-3734c7f7-dc3f-4d2f-8a1b-086d57994bdf.png)

### Easy Ensemble AdaBoost Classifier

- Accuracy Score: 93%
- Precision High Risk: 7%
- Precision Low Risk: 100%
- Recall High Risk: 91%
- Recall Low Risk: 94%

![Easy_Ensemble_AdaBoost_Classifier](https://user-images.githubusercontent.com/94089680/164948110-2ae5d317-4f30-4f6b-bf56-9a3a220805d8.png)

## Summary
In this project, we are trying to find out the best model to evaluate if the loan is high risk or not. In order to achieve our goal, we need to find a model that let the least amount of high risk loans pass through undetected. We would like to get the accuracy rate closer to 1. In this dataset, the precision scores for all models are within an  appropriate range. However, the result concluded the Easy Ensemble AdaBoost Classifier is the best model for the credit risk analysis. The accuracy scores is 93% in the Easy Ensemble AdaBoost Classifier model. The rest of the models have the accuracy scores are below 80%. In this model, the Easy Ensemble AdaBoost Classifier has the highest recall score among all models. Therefore, it is the final best machine learning model to choose for further credit card analysis.