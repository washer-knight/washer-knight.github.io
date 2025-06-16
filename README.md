****Context/background info****

-Variables of Interest: Bank loan received in applications for purchasing property and 
applicant’s income 

-Dependent Variable: Loan amount in thousands  

-Independent Variable: Applicant’s income in $1000s 

-Original Data: Wooldridge Data Sets, Loanapp, US cross sectional data on loan 
applications for purchasing property 

-Description of the dependent variable Loan amount 

-Description of the independent variable Applicant’s income

-------------------------------------------------------------------------------------------------
****How might the two variables of interest be related theoretically?****

-Their relationship is based on the applicant's affordability and income is the key factor of it. 
-The two variables—loan amount and applicant’s income, are positively correlated; which is to say that
as the applicant's income increases, the loan amount received from the banking institution will also increase and vice-versa.

--------------------------------------------------------------------------------------------------
****Summary statistics & Table****

![Image](https://github.com/user-attachments/assets/b05ec9dc-7738-487c-99ef-4d0633b24164)
![Image](https://github.com/user-attachments/assets/2a4a7a62-ea62-4138-897d-a35d5bcbeb7e)
![Image](https://github.com/user-attachments/assets/f8cc1026-523e-45ff-8af1-b7d678c6ad8d)

--------------------------------------------------------------------------------------------------
****Discussion of the data****

****Mean****
- 143 is the mean data/distribution center of the Loan amount in 1000s
- 84.7 is the mean data/distribution center of the Applicant's income in 1000s

****Median****
- 126 is the midpoint of the Loan amount in 1000s. Min:2; Q3:165; Max:980.
- 64 is the midpoint of the Applicant's income in 1000s. Min:0; Q3:88; Max:972.

****Std Dev****
- From these statistics, we know the data is extremely skewed

------------------------------------------------------------------------------------------------------

****Histogram****

The Histogram will be used to illustrate this:

![Image](https://github.com/user-attachments/assets/faa97fe9-6a1b-4434-a5ef-52967fbaa8f3)

![Image](https://github.com/user-attachments/assets/d3e44624-3d01-487c-8810-38ed1e22e8d6)

![Image](https://github.com/user-attachments/assets/3d254dce-0fe2-446f-9b4e-ae8f20db6d5e)

---------------------------------------------------------------------------------------------------------

****Histogram Discussion****

****Modality:****
 - Both the shapes of these two histograms have a single prominent peak(unimodal)

****Skewness:****
 - Both the shapes of these two histograms are Left Skewed.

****Applicant's Income(in1000s)****
 - Relatively more common among 0~200.
****Bank Loan Amount(in1000s)****
 - Relatively more common among 0~250.

****Unusual Observations:**** (x= appinc; y=loanamt)
 - Yes. For example: (666,121), (666,133), (351,632), (972,360).
 - This is shown clearly in the linear regression model below
 
---------------------------------------------------------------------------------------------------------
****Linear Regression Model****

![Image](https://github.com/user-attachments/assets/7b9e9f63-5a93-479c-b014-30832ae80e97)

![Image](https://github.com/user-attachments/assets/21344a5a-2eca-4109-b705-3e3757f64231)

![Image](https://github.com/user-attachments/assets/b38bbeca-1f0c-410c-a610-59dc6149ca64)

---------------------------------------------------------------------------------------------------------

****Linear Fit Estimation****

****Response variable?****
 - Loan amount in thousands 

****Explanatory variable?****
 - Applicant Income in 1000s

****Relationship:****
 - linear
 - positive
 - moderately strong



The scatterplot above shows the relationship between Applicant's income in 1000s and Loan amount in thousands (1989 observations of 2 variables).






