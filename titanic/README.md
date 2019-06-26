# Titanic: Machine Learning from Disaster README

### Authors
Farah
Murtadha

### Date

31st Mar 2019

### Website

### Kaggle score

0.7
---


### Problem Statement

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this project, we try to analyze what sorts of people were likely to survive. In particular, we apply the tools of machine learning to predict which passengers survived the tragedy.

SOURCE: [Kaggle](https://www.kaggle.com/c/titanic)

---


### Executive Summary
We first import two sets of data, one is for training and another for prediction. We second do some cleaning on the data entries of both sets including investigating the data types of each variable. At the end of the cleaning stage we provide a heatmap for the different variables in the set.

The second part of this project is performing some feature engineering to the variables. Some of the tasks done over this part includes  filling the NaN cells with proper values in each columns, combining different variables with each other to create more useful feature, and mapping categorical variables into numerical type. At the end we drop some variables that we find it irrelevant to modeling.

The last part is modeling. In this part we compare different classifiers models scores using k-Fold cross-validation techniques. We store all scores in a dictionary and we pick a model with the highest score.

Finally, we fit the data into the best model and we predict for the test sample.
---

### Data Dictionary

Variable | Definition                                 | Key                                            |
----------|--------------------------------------------|------------------------------------------------|
 survival | Survival                                   | 0 = No, 1 = Yes                                |
 pclass   | Ticket class                               | 1 = 1st, 2 = 2nd, 3 = 3rd                      |
 sex      | Sex                                        |                                                |
 Age      | Age in years                               |                                                |
 sibsp    | # of siblings / spouses aboard the Titanic |                                                |
 parch    | # of parents / children aboard the Titanic |                                                |
 ticket   | Ticket number                              |                                                |
 fare     | Passenger fare                             |                                                |
 cabin    | Cabin number                               |                                                |
 embarked | Port of Embarkation                        | C = Cherbourg, Q = Queenstown, S = Southampton |
---
