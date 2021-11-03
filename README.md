# introml

You can also get here from:  https://bit.ly/DS2121

To run the code - click the mybinder button:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fenago/introml/HEAD)

The Regression Algorithm data comes from:
https://www.kaggle.com/CooperUnion/cardataset

The Classification Algorithm:

The Clustering Algorithm data comes from:
https://www.kaggle.com/arjunbhasin2013/ccdata


Universal Bank is a relatively young bank growing rapidly in terms of overall customer 

acquisition.  The majority of these customers are liability customers (depositors) with 

varying sizes of relationship with the bank.  The customer base of asset customers 

(borrowers) is quite small, and the bank is interested in expanding this base rapidly to bring 

in more loan business.  In particular, it wants to explore ways of converting its liability 

customers to personal loan customers (while retaining the as depositors).

A campaign that the bank ran last year for liability customers showed a healthy conversion 

rate of over 9% success.  This has encouraged the retail marketing department to devise 

smarter campaigns with better target marketing.  The goal is to use KNN to predict whether 

a new customer will accept a loan offer.  This will serve as the basis for the design of a new 

campaign.

The UniversalBank data set contains data on 5000 customers.  The data include customer 

demographic information (age, income, etc.), the customer’s relationship with the bank 

(mortgage, securities account, etc.), and the customer response to the last personal loan 

campaign (Personal Loan).  Among these 5000 customers, only 480 (9.6%) accepted the 

personal loan that was offered to them in the earlier campaign.


a. Transform categorical predictors with more than two categories into dummy 

variables, then partition the data into training (60%) and validation (40%) sets.

b. Consider the following customer:

Age=40

Experience=10

Income=84

Family=2

CCAvg=2

Education_1=0

Education_2=1

Education_3=0

Mortgage=0

Securities Account=0

CD Account=0

Online=1

Credit Card=1

Perform a KNN classification with all predictors except ID and ZIPcode using k=1.  

Specify the success class as 1 (loan acceptance) and use the default cutoff of 0.5.  

How would this customer be classified?


c. What is a choice of k that balances between overfitting and ignoring the 

predictor information (i.e., the best k)?


d. Show (and explain) the classification matrix for the validation data that results from using the best k.


e. Classify the customer from above using the best k.


f. Briefly explain your results and how they would be useful to Universal Bank.
