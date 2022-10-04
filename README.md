# Credit-Crad-Fraud-Detection

The Credit Crad Fraud base dataset used in this work is made available by MACHINE LEARNING GROUP and downloaded from Kaggle. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. Link for the dataset : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?datasetId=310&sortBy=voteCount. 

![Libraries](https://user-images.githubusercontent.com/103879211/193762065-dac98673-1ca8-4731-8a3c-1977f522d079.jpg)

## Objectives
This work is acrried out to answer this problem :
1. How to identify the new transaction is fraudlent or not?
2. The goal is to detect 100% of fraudlent transactions while minimizing the classification of fraudlent frauds incorrectly.

## Libraries
Libraries such as pandas, Numpy, matplotlib, and seaborn are the most commonly used in the analysis. However, I also used sklearn to conduct the predictive analysis with some classification models.

## Result Preview 
By Hyperparameter Tuning, it is found that Logistic Regression gives the best result compared to Random Forest with precision 99% and F1-score 95.7%

![Confusion Matrik Logistic Regression Tuned](https://user-images.githubusercontent.com/103879211/193762063-e126101d-fab8-41ca-9675-cf734e5fd488.png)

Our Best model Logistic Regression correctly predicted 96 of the 104 frauds and it's not wrong mark fraud when people aren't cheating
