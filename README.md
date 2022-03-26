# Starbucks Capstone Challange
## Motivation
#### Project Overview
This python notebook is part of my capstone project for the Data Science Nanodegree from Udacity. The provided data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once in a while Starbucks sends offers to their customers through different channels, e.g. Email or Social Media. These offers vary for different users and range from simple advertisements up to discounts like "buy one get one free".

#### Problem Statement
The problem I chose to solve is to predict if a customer will respond to an offer. To achieve this, I will train a model with a combination of the transaction and profile data.

## Results
After the data preprocessing I chose five different classifiers to test. All five classifiers had roughly the same performance. This part was unexpected, although I used grid search to optimize each of the classifiers. The unexeptional scores of accuracy with 0.74 and a F1-score with 0.73 (0.74 for MLP) was not unexpected though. The randomness of the data is tricky to deal with: even the same person may respond to the same offer differently on a different day.

The analysis of the feature importances showed that both customer and offer features are important whether an offer is successful or not. For the customer features income and age are most important and reward, difficulty and duration for the offer features.

## This project was created with the following environment:
- python 3.8.10
- numpy-base 1.20.2
- pandas 1.2.4
- scikit-learn 0.24.2

## Files & Data

[Starbucks_Capstone_notebook.ipynb](https://github.com/dzils/starbuckscapstonechallange/blob/main/Starbucks_Capstone_notebook.ipynb) - The notebook used to solve the problem

[Starbucks_Capstone_notebook.pdf](https://github.com/dzils/starbuckscapstonechallange/blob/main/Starbucks_Capstone_notebook.pdf) - The .pdf version of the notebook

 The data was provided by [Udacity](https://www.udacity.com/).
 #### - ./data
 Contains the data files used in this project
