
# Default of credit card clients

### Dateset information
This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005

### Problem Statement
The problem finding the patterns in customer behaviors that help predicting if a customer have a chance of getting his credit card defaulted before the 6 months period. By applying the right algorithm and parameters we can get a prediction on the 5th month or even 4th month to know if the customer have high chance of getting his credit card defaulted

### Objectives 
- We will get to know How does the probability of default payment vary by categories of different demographic variables.
- We will build a prediction model by using this we will able to predict which customer will default next month or not.

### Attribute Information
1. ID: ID of each client
2. LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit
3. SEX: Gender (1=male, 2=female)
4. EDUCATION: (1=graduate school, 2=university, 3=high school, 4=others, 5=others, 6=others, 0=others)
5. MARRIAGE: Marital status (1=married, 2=single, 3=others, 0=others)
6. AGE: Age in years
7. PAY_0: Repayment status in September 2005 (-1=pay duly, 1=payment delay for one month, 2=payment delay for two months, … 8=payment delay for eight months, 9=payment delay for nine months and above)
8. PAY_2: Repayment status in August 2005 (scale same as above)
9. PAY_3: Repayment status in July 2005 (scale same as above)
10. PAY_4: Repayment status in June 2005 (scale same as above)
11. PAY_5: Repayment status in May 2005 (scale same as above)
12. PAY_6: Repayment status in April 2005 (scale same as above)
13. BILL_AMT1: Amount of bill statement in September 2005 (NT dollar)
14. BILL_AMT2: Amount of bill statement in August 2005 (NT dollar)
15. BILL_AMT3: Amount of bill statement in July 2005 (NT dollar)
16. BILL_AMT4: Amount of bill statement in June 2005 (NT dollar)
17. BILL_AMT5: Amount of bill statement in May 2005 (NT dollar)
18. BILL_AMT6: Amount of bill statement in April 2005 (NT dollar)
19. PAY_AMT1: Amount of previous payment in September 2005 (NT dollar)
20. PAY_AMT2: Amount of previous payment in August 2005 (NT dollar)
21. PAY_AMT3: Amount of previous payment in July 2005 (NT dollar)
22. PAY_AMT4: Amount of previous payment in June 2005 (NT dollar)
23. PAY_AMT5: Amount of previous payment in May 2005 (NT dollar)
24. PAY_AMT6: Amount of previous payment in April 2005 (NT dollar)
25. default.payment.next.month: Default payment (1=yes, 0=no)

### Library Used
Numpy  
Pandas  
Matplotlib  
Seaborn  
Sklearn  
Xgboost







