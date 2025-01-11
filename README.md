# Project_Data-mining-and-Statistics
Project on Predicting risk level of Covid19 Patients

## Overview
This project focuses on predicting the severity of illness in COVID-19 patients using machine learning models. By analyzing patient data, including symptoms, medical history, and demographic details, the goal is to assist healthcare providers in better utilizing resources and improving patient care outcomes.

## Dataset
The dataset, sourced from Kaggle, contains real-time COVID-19 patient information with approximately 1 million rows and 21 columns, providing a comprehensive set of predictors for model development.

## Approach
### Data Preprocessing: 
Cleaned and prepared the data, splitting it into 80% for training and 20% for testing.
### Exploratory Data Analysis (EDA): 
Identified key correlations, such as age, intubation, and ICU admission, with patient outcomes.
### Dimensionality Reduction: 
Applied Principal Component Analysis (PCA) to uncover patterns and reveal six distinct clusters within the data.
### Clustering: 
Used K-means clustering to segment the dataset into meaningful groups.
### Modeling: 
Applied multinomial logistic regression to each cluster individually to improve prediction accuracy.

## Results
The proposed method achieved a predictive accuracy of 51%, a significant improvement over the 16% accuracy obtained when applying logistic regression to the entire dataset. This demonstrates the value of clustering and tailored modeling approaches in improving predictive performance.

## Key Takeaways
Clustering data before applying predictive models can uncover latent patterns and significantly enhance model accuracy.
The project underscores the importance of tailored approaches in machine learning for healthcare applications.

