# Chronic-Kidney-Disease-Diagnosis-Using-Machine-Learning-Algorithms

![A-Machine-Learning-Methodology-for-Diagnosing-Chronic-Kidney-Disease](https://user-images.githubusercontent.com/128668596/228056834-82a9f7be-bbff-462b-b13c-d0ed0a1ac7c3.jpg)

In this project, I propose a machine learning methodology for diagnosing CKD, which is a global health problem with high morbidity and mortality rate, and it induces other diseases.

In recent years, people worldwide have been suffering from various types of kidney diseases indescribably, among which chronic kidney disease (CKD) has exacerbated the situation. Early diagnosis of CKD is the only way to hinder the advancement of kidney disease in its initial stage. However, presently doctors can use machine learning classifier algorithms to identify the disease earlier than any other existing method. Here, this research work presents a method by using eight different machine learning (ML) algorithms that can promptly detect the infection of CKD considering the health condition dataset information of the patient. A dataset is used of nearly two months of that period delivered by the hospital to identify the plausibility of chronic kidney disease. This research study has used the Extra Tree Classifier (EXT), AdaBoost (ADB), K-Nearest Neighbors (KNN), Gradient Boosting (GB), Extreme Gradient Boosting (XGB), Decision Tree (DT), Gaussian Naïve Bayes (GNB) and Random Forest (RF) to obtain an optimum result of prediction. After preprocessing the data, this research work has applied the ML algorithms and compared their performances, and eventually, the precise outcome has been obtained. The performance is analyzed by using the F1-score, precision, accuracy, recall, and AUC score. According to the analysis results, K-Nearest Neighbors and Extra Tree Classifier have performed better than other algorithms for achieving an accuracy of 99% preceding the Gradient Boost, which stands at 98%.

## Table of Contents
1. Data Pre Processing
2. EDA
3. Feature Encoding
4. Model Building
    * Knn
    * Decision Tree Classifier
    * Random Forest Classifier
    * Ada Boost Classifier
    * Gradient Boosting Classifier
    * Stochastic Gradient Boosting (SGB)
    * XgBoost
    * Cat Boost Classifier
    * Extra Trees Classifier
    * LGBM Classifier
5. Models Comparison


## Exploratory Data Analysis (EDA)
![download-1](https://user-images.githubusercontent.com/96882935/227001408-3185a485-6328-4542-a67d-710c049355f0.png)


![newplot (2)](https://user-images.githubusercontent.com/96882935/227001528-40ffce2d-1f0c-4d38-bb57-7991fb34a6a2.png)


![newplot (3)](https://user-images.githubusercontent.com/96882935/227001592-a57bf44a-46f0-4a47-8d6f-4acbd5ec5b16.png)

![newplot (5)](https://user-images.githubusercontent.com/128668596/228057912-b3537c0a-5b9e-4b25-88bf-d5a9639df46f.png)

<img width="765" alt="Screenshot 2023-03-27 at 3 19 54 PM" src="https://user-images.githubusercontent.com/128668596/228058052-89cfa1e2-ac05-4bdf-97c1-651987122467.png">

## Model Building
<img width="630" alt="Screenshot 2023-03-22 at 1 26 23 PM" src="https://user-images.githubusercontent.com/96882935/227002024-72adb4be-a6b6-4ba1-8a74-7e7b6a6e41a8.png">


## Models Comparison

![newplot (4)](https://user-images.githubusercontent.com/96882935/227002113-3d34e4c9-45d1-4d55-ac05-050426ad64e6.png)

## Summary of Results
We have successfully built the Flight Price Prediction Machine Learning Model to predict and classify patience as having chronic kidney disease (ckd) or not. The stop three model we should use are Random Forest Classifier, Cat Boostm, and Gradient Boosting Classifier.
