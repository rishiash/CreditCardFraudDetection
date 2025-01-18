# Credit Card Fraud Detection
> Predict fraudulent credit card transactions with the help of machine learning models.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Goal is to predict fraudulent credit card transactions with the help of Machine learning models. 
- The data set is highly unbalanced. Class balancing was performed using Random Sampling, SMOTE and ADASYN techniques.
- Exploratory data analysis has been conducted for all continuous and categorical variables
- Different machine learning models have been tried - Logistic Regression, Random Forests, XGBoost
- Hyperparameters have been tuned

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Random sampling is performing better in terms of precision but Sensitivity is slightly lower compared to SMOTE and Adasyn.
- I have chose ADASYN sampling with XGBoost as the final model
- SMOTE sampling with XGBoost also give equivalent results
- 0.75 probability cutoff appears to be giving the optimal results

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was part of our learning for ML C56
- The project was worked by Rishi


## Contact
Created by [@rishiash] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
