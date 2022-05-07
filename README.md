# Credit-card-Default-prediction:
  * Financial threats are displaying a trend about the credit risk of commercial banks as the incredible improvement in the financial industry has arisen. 
  * In this way, one of the biggest threats faced by commercial banks is the risk prediction of credit clients.
  * The goal is to predict the probability of credit default based on credit card owner's characteristics and payment history.

### Dataset:
  * Categorical features : sex, education, marriage
  * Continuous features : age, amount of given credit
  * Payments - Repayment status, Amount of bill statement, Amount of previous payment.


### EDA findings:
  * Defaulters are less as compared to the Non-Defaulters in the given dataset. The dataset is skewed towards 1 class. Hence we need to balance the dataset.
  * Number of Male credit card holder is less than Female.
  * More number of credit card holders are university students followed by Graduates and then High school students.
  * More number of credit card holders are Single.
  * No:of credit card holders are high between age 23 to 40.
  * Default mostly happens when amount of credit is less than 2,00,000.
  * Payment delay beyond 2 months is very less.
  * Previous payment amount of Defaulters is less than that of non-defaulters.
  * Bill statement for defaulters is less than that of non-defaulters.

### Feature Engineering:
  * cleaning, encoding, feature selection

### Models used:
  * Logistic regression, Decision tree classifier
  * Random forest classifier, Xgboost

### Metrics used:
  * accuracy, precision, recall, f1 score, auc-roc

### Conclusion: 
  * Random forest model gives the best score of 91%
