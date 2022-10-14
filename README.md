# (Prosper Loan Data)
## by (Boris MVE MANGA)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate, Interest rate, current loan status, borrower income, Monthly Loan Payments, Borrower State, Loan term and many other features.


## Summary of Findings

In the exploration phase, i found many interesting findings. Below are some of the results we got during this phase :

>**49.7%** of Loan are **Current**, **33.4%** of Loan are **Completed**, **4.4%** of Loan are **Defaulted** 
>The Most used PropserRating are : **C, B** and **A** 
>**77%** of Loan Term is **36 Months**; **21.5%** is **60 months** and **1.4%** is **12 months** 
>**12.3%** are **Professionals**; **4.1%** are **Computer programmers** and **25.9%** have different occupation than the most common 
>Most of the Borrowers rate is between **0.10** and **0.20** 
>The top 5 Sates with more Borrowers are : **California, Texas, New York, Florida, Illinois** 
>Most of the Borrowers monthly income is between **100** and **500** dollars 
>**60.3%** of the Borrowers are **Employed**, **0.7%** are **Not Employed** and **5.5%** are **Self-Employed** 
>Income is verifiable for **92.4%** of the Borrowers 
>The Loan Original Amount is between **1000** and **10000** for the majority 
>There is a **Strong positive** correlation between **BorrowerAPR** and **BorrowerRate**  
>There is a **negative correlation** bewteen the **BorrowerRate** and **ProsperScore**.This negative correlation is different for each Loan **Term** 
>There is a positive Correlation for each value of **Term** bewteen **LoanOriginalAmount** and **MonthlyLoanPayment** 
>There is a negative correlation between **BorrowerRate** and **ProsperScore**.This negative correlation if different if the Borrower is Owner or Not 


## Key Insights for Presentation

>For the presentation, we'll presnt the multivariate correlation between  **LoanOriginalAmount** and **MonthlyLoanPayment** based on **Loan Term** : We found that there are 3 positive correlation between *LoanOriginalAmount* and *MonthlyLoanPayment*. Each Regression line is based on a specifica value of *Loan Term* (36, 60 or 12) 

>Then we'll present the correlation between **ProsperScore** and **BorrowerAPR** based on Loan term : We found that there are 3 negative correlation lines between *ProsperScore* and *BorrowerAPR* and each line is determined by a specific value of *Loan Term*

>We are then presenting the **Loan Term** distribution : We found that *77% of Loan are for 3 Years*, *21.5% are for 5 years* and *1.4% are for 1 Year* 

>We are then presenting the **BorrowerStatus** distribution and also the Loan term distribution : We found that Comments : *60.3% of Borrowers are Employed*, *5.5% are Self-Employed* and *0.7% are not Employed*
