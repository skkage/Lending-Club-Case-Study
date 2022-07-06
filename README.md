# Lending Club Case Study
> Outline a brief description of your project.
The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Analyze the contents of loan.csv and derive conclusions.
- The data has the history 2007 to 2011 about the loan applications that have been approved and various factors against which loans were approved.
- Identify the features/variables that will be able to help identify if new applications will default or not if approved.
- Loan.csv is the data set which is being used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### - Conclusions from Univariate analysis

1. There are 85% fully paid applicants.
2. Around 75% of loan applicants prefer 36 months of loan term.
3. Applicants are mostly categorized on grade B (B3 major subgrade) followed by grade A (A4 major subgrade) based on the base rate and risk.
4. The major loan applicants are from employees who have more than 10 years of exp.
5. People who rent/ mortgage out the homes are the major applicants. The applicants who are home owners are least.
6. Most of the applicants are not verified.
7. Applicants usually take loans for debt consolidation.
8. Most of the applications are from CA address.
9. Around 4.2 percent of users have atleast 1 bank bankruptcies cases registered against them.
10. Applicants are mostly looking for loans between 5K to 10K. On an avg we see the loan applicants looking for loan amount from 500 to 25K
11. Most of the loans have an interest rate of Medium followed by medium high and low. There are very minimal loans given to users which very high interest rate.
12. Most of the loan applicants have an annual income of 25K to 50K followed by 50K to 75K range.
13. Most of the loan as issued in the month of Dec - probably the year end people want to pay/close their debts.
14. There is a significant growth in people using the lending club to borrow loans and the nos have grown from near 0 to 20000 loans being provided from 2007 to  2011 year showing the prospects of company growing


### - Conclusion 2 from Bivariate Analysis

1.Loan applicants with the grade B5 have the highest no of charged off accounts followed by B3 and B4 in grade B. Followed by grade C - C1 and C2
2. So in general people who are provided loans graded B and C have high probablitiy of defaulting the loan.
3. Looks like employees with more than 10 years of experience are likely to have more loan defaults compared to others.
4. Loan applications having anual income between 25K to 50K are likely to have more loan defaults compared to others. 5. Loan applications who dont own a house are more likely to default a loan.
5. Loan applications who are taking loan for the purpose of debt consolidation are more likely to default the loan
6. Loan applications from CA address are more  likely to default the loan
7. Loan applications having the interest rate between M and MH are more  likely to default the loan

### - Conclusion 3 from Multi Variate Analysis

With respect to loan_status which is the target - dti has got the highest correlation with loan status. I.e if the debt to income increases the loan applicant tends to default the loan as he has more debt to be repaid than his income 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python libaries
- - Pandas
- - Numpy
- - Matplotlib
- - Seaborn
- - Warnings
- - EDA techiniques to clean up the data

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->




## Contact
Created by [@skkage] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project --># Lending-Club-Case-Study
# Lending-Club-Case-Study-
