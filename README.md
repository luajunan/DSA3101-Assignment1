# Project: Predicting Loan Defaults in Bank

## Project Description

This is a machine learning project done on a Kaggle Dataset: https://www.kaggle.com/arkapravasen/bank-loan-default

Data Science Techniques:
1. Exploratory Data Analysis
2. Point Biserial Correlation
3. Pearson's Correlation
4. Cramer V's Correlation 
5. Logistic Regression
6. Random Forest Classifier
7. Gradient Boosting Tree Algorithms (XGBoost)

## Objective of Project

1)	To reject the individuals who are at very high risks of defaulting

2)	To ensure that individuals capable of repaying are given the loan

3)	To scale down the loans given to individuals at higher default risk to reduce potential losses while enabling potential gains

In short, banks consider an individual who was given the loan yet defaulted as a false positive whereas an individual who was not given the loan yet could have repaid on time is considered as a false negative. 

In both cases, since banks missed out on an opportunity to profit, they are interested in reducing the amount of false positives and false negatives.

## Final Model and Impact of Project

After several iterations, our group decided to go with the `XGBoost` model which gave the best scores across various metrics.

| **Metrics** | **Score** |
| ------------- | ------------- |
| F1 | 74.6%  |
| Recall | 77.6%  |
| Precision | 71.8%  |
| Accuracy | 73.5%  |

### Evaluation of Project

#### Greater approval rate by lowering loan amount given to clients

With this, we can potentially lower losses **by $762,597,495.00 (or 18.23%).** This is because clients, albeit the lower loan amount granted, will still have to pay interest. As such, the bank still gains a semblance of revenue. This is favoured rather than completely losing potential income by rejecting the clients upfront.


#### Providing better repayment process for younger adults

With this, we expect **an increase of $393,106,511.23 (or 8.03%) in interest income gained** from customers below the age of 25.

# Team Contributors

1. [Lua Jun An](https://github.com/luajunan)
2. [Keith Tay Xiang Rui](https://github.com/keith-tay)
3. Tu Zhehao
4. Timothy Wong Hoey Pheen
5. [Ahmad As-Shodiqqul Amin](https://github.com/shodiqqul)
6. Dione Lim Yee Sze
7. Kellie Chin Shu Wen
8. Ni Hui Ling


