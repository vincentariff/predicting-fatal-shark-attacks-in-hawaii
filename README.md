# Predicting Fatal Shark Attacks in Hawaii

## Table of Contents

* [Introduction](https://github.com/vincentariff/predicting-fatal-shark-attacks-in-hawaii#introduction)
* [Dataset](https://github.com/vincentariff/predicting-fatal-shark-attacks-in-hawaii#dataset)

## Introduction

* In this project, I predict whether an unprovoked shark attack involving Tiger sharks in Hawaii will result in a fatality.

* The data was scraped and cleaned into a suitable format, engineered new features based on domain knowledge, addressed outliers, applied one-hot encoding, and scaled the data. We built logistic regression models, addressed class imbalance by upweighting the minority class, optimized the model with GridSearchCV, and validated performance using cross-validation. The model was evaluated using various metrics, and its coefficients were interpreted in terms of odds to identify the features with the greatest impact on the likelihood of a Tiger shark attack being fatal.

*  The final model received a generalized accuracy score of 95.53%. While the likelihood of a tiger shark attack is low, this model can assist in determining when conditions are least conducive to a fatal encounter.

## Dataset

* The dataset _hawaii_shark_attacks.csv_ was scraped from [Hawaii.gov](https://dlnr.hawaii.gov/sharks/shark-incidents/incidents-list/).
