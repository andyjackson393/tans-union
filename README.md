# tans-union
ML Problem of trans union
Classify the credit score

Problem Statement
-----------------

You are working as a data scientist in a global finance company. Over the years, the company has collected basic bank details and gathered a lot of credit-related information. The management wants to build an intelligent system to segregate the people into credit score brackets to reduce the manual efforts.

**Task** 

Given a person’s credit-related information, build a machine learning model that can classify the credit score.

Dataset description
-------------------

The dataset contains the following files: 

*   _train.csv_: 100000 x 28
*   _test.csv_: 50000 x 27
*   _sample\_submission.csv_: 5 x 2 

 The columns provided in the dataset are as follows:
 
|Column Name|Description|
|--- |--- |
|ID|Represents a unique identification of an entry|
|Customer_ID|Represents a unique identification of a person|
|Month|Represents the month of the year|
|Name|Represents the name of a person|
|Age|Represents the age of the person|
|SSN|Represents the social security number of a person|
|Occupation|Represents the occupation of the person|
|Annual_Income|Represents the annual income of the person|
|Monthly_Base_Salary|Represents the monthly base salary of a person|
|Num_Bank_Accounts|Represents the number of bank accounts a person holds|
|Num_Credit_Card|Represents the number of other credit cards held by a person|
|Interest_Rate|Represents the interest rate on credit card|
|Num_of_Loan|Represents the number of loans taken from the bank|
|Type_of_Loan|Represents the types of loan taken by a person|
|Delay_from_due_date|Represents the average number of days delayed from the payment date|
|Num_of_delayed_Payment|Represents the average  number of payments delayed by a person|
|Changed_Credit_Limit|Represents the percentage change in credit card limit|
|Num_Credit_Inquiries|Represents the number of credit card inquiries|
|Credit_Mix|Represents the classification of the mix of credits|
|Outstanding_Debt|Represents the remaining debt to be paid (in USD)|
|Credit_Utilization_Ratio|Represents the utilization ratio of credit card|
|Credit_History_Age|Represents the age of credit history of the person|
|Payment_of_Min_Amount|Represents whether only the minimum amount was paid by the person|
|Total_EMI_per_month|Represents the monthly EMI payments (in USD)|
|Amount_invested_monthly|Represents the monthly amount invested by the customer (in USD)|
|Payment_Behaviour|Represents the payment behavior of the customer  (in USD)|
|Monthly_Balance|Represents the monthly balance amount of the customer (in USD)|
|Credit_Score|Represents the bracket of credit score (Poor, Standard, Good)|


Evaluation metric
-----------------

    score = roc_auc_score(actual, predicted, average= "weighted",multi_class='ovr')

Result submission guidelines
----------------------------

*   The index is "ID" and the target is the _"_Credit\_Score" column. 
*   The submission file must be submitted in _.csv_ format only.
*   The size of this submission file must be 50000 _x 2_.

_Note_: Ensure that your submission file contains the following:

*   Correct index values as per the _test.csv_ file
*   Correct names of columns as provided in the _sample\_submission.csv_ file

[Dataset](https://drive.google.com/drive/folders/18uR4CieHNf0i83bVt7ac9cv9SGkImjIM?usp=sharing)
