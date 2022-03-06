# ProsperLoan Data Exploration

## Dataset

This [Prosper Loan Dataset](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547699802003000)
contains 113,937 loans with 81 variables on each loan, including loan amount, 
borrower rate (or interest rate), current loan status, borrower income, and many others.
The [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp=sharing) explains the 
variables in the data set.
The project objective is not expected to explore all of the variables in the dataset. A subset of were chosen to be analyzed.

## Summary of Findings


•LoanStatus of all Borrowers are with current and completed state;
•EmploymentStatus of all Borrowers are with Employed State;
•Majority of the loan applicants are from 50K to 75K range with emloyeed status;
•The distribution of monthly income of applicants is a right skewed because there will be few applicants with high salary; 
•Applicants with incomerange of 50K to 75K range have their prosper rating falling under AA, A, B and C;
•LoanStatus with current and completed have own homes when they applied for loans;
•The monthly income of borrowers are having higher values for employed, other and full time employment status with the prosper rating of AA, A and B;
•We observe that without homeowner tend to have a higher interest rate, and thus lower rating.However homeowner tends to have lower interest rate and higher rating. So we can safely say that homeowner is safest bet when gving a loan. We can also clearly observe that HR prosper rating applicants have higher interest rates.


## Key Insights for Presentation

For the slide presentation, I focused mainly with the features that are impactful for approval of the loanstatus.
The exploration starts by looking at the distrbuiton of each and every numeric and categorical variables and all the necessary univariate, bivariate and
mulitvariate analysis on the selected variables.

The mmain insights obtained are :


•LoanStatus of all Borrowers are with current and completed state;
•EmploymentStatus of all Borrowers are with Employed State;
•Top IncomeRange of all Borrowers are within $50,000-74,999;
•Majority of the borrowers are with an occupation of Professional and Executive;
•Majority of the borrowers are with a rating or score from 4 to 8;
•The borrowers rate follow an approximately unimodal distribution, with the peak around 0.16; 
•The origination amount of the loan is interesting. Here we see that the distribution is a right skewed with multiple peaks observed at 4000 USD, 10000 USD and 15000 USD;
•Loan original amount and monthly loan payment is highly correlated and it is expected and borrowers interest rate and proper score are highly correlated. Borrower interest rate and loan amount are correlated too.


This work focused on the analysis of the Prosper Loan Data. The analysis covered univariate, bivariate and multivariate data analysis. Many plots and statistics were made to help the visualization and insight gain of the data. To conclude this analysis, I'd say that the loan approval status is heavily dependent on the applicant's information on IncomeRange, Homeownerstatus and employment status.
