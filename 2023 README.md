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
- The data is extremely skewed

------------------------------------------------------------------------------------------------------

****Histogram****

![Image](https://github.com/user-attachments/assets/faa97fe9-6a1b-4434-a5ef-52967fbaa8f3)

![Image](https://github.com/user-attachments/assets/d3e44624-3d01-487c-8810-38ed1e22e8d6)

![Image](https://github.com/user-attachments/assets/3d254dce-0fe2-446f-9b4e-ae8f20db6d5e)

---------------------------------------------------------------------------------------------------------

****Histogram Discussion****

****Modality:****
 - Both the shapes of these two histograms have a single prominent peak (unimodal)

****Skewness:****
 - Both the shapes of these two histograms are Left Skewed.

****Applicant's Income (in 1000s)****
 - Relatively more common among 0~200.
****Bank Loan Amount (in 1000s)****
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

![Image](https://github.com/user-attachments/assets/99ec9a23-4c6d-40ab-81bd-59c12bed5e5a)

 - The scatterplot above shows the relationship between Applicant's income in 1000s and Loan amount in thousands (1989 observations of 2 variables).

---------------------------------------------------------------------------------------------------------

****Interpretation of the estimated relationship****
 - The estimated relationship between loan amount in 1000s and applicant's income in 1000s is a measure of how these two variables are related to each other. 
 - It is represented by a regression line that shows the expected loan amount given an applicant's income level.
 - By computing the data via R.Studio, the correlation between the two variables is **0.4334031** (moderately strong).
 - As the relationship is **positive(+)**, it means that loan amounts tend to increase with increasing income levels. This could indicate that lenders are more willing to provide larger loans to applicants who have higher incomes, as they may be seen as less risky borrowers.

![Image](https://github.com/user-attachments/assets/f21db383-83f7-4cb2-a4ba-648443c18a92)

**Statistics**

![Image](https://github.com/user-attachments/assets/fdb92571-4b1c-4107-a276-260d5445bfa2)

![Image](https://github.com/user-attachments/assets/dce98bb7-0b5b-4b36-bd9c-a782f7363d62)

![Image](https://github.com/user-attachments/assets/31aabe3f-a474-4f8f-bc48-cf04cbe74493)

![Image](https://github.com/user-attachments/assets/8d38b333-9e79-4ae9-826f-10b4560b95f6)

**Intercept**

 - The y intercept of the linear regression chart is 109.3018
 - This tells us that if the independent variable (applicant's income) is zero, then we should expect a bank loan of $109,301.8
 - In this case, it probably makes sense to not interpret the intercept, as it is unplausible that someone with an income of zero should be able to get a loan anywhere near this size.

**Slope**

 - In this case, the slope is positive, meaning that as income increases, the banks are willing to give applicants larger loans.
 - This may be because those with a higher income will be more likely able to pay off a higher loan, so are seen as safer borrowers.
 - This works the other way too, where a lower income is seen as a less safe borrower so receive a smaller loan. 
 - Upon extending the slope, it starts to make less sense, as where income tends towards zero it is unlikely that a borrower can pay back anywhere near the $109,301 loan suggested by the slope.
  - As the income tends towards infinity, the slope comes into another issue as the banks don’t have infinite money, so there is a limit as to how much they would be willing/ able to lend.

**R-Squared**

 - R-squared: 0.188,  Adjusted R-Squared: 0.187
 - 0 = regression explains none of the variability. 
 - 18.7% of the variability in the Loan amount in thousands among 1989 observations is explained by the model. 
 - As R-squared = 0.188, the relationship is weak, however there is still a positive correlation. 
 - As income increases, so does the loan amount.

---------------------------------------------------------------------------------------------------------

**Conclusions**

 - There is a positive relationship between loan amount (in 1000s) and applicants income (in 1000s)
 - As income increases banks are able to loan larger amounts. 
 - Applicants with a higher income is more likely to be able to pay off a higher amount rather than someone with a lesser income.
 - The relationship is only moderately strong, therefore it can be concluded that outside factors, such as credit score, existing assets and wealth, may also have an influence on the loan amount given. This could also be a reason as to why the intercept is $109,301 for those with an income of 0, rather than a smaller amount that would be more manageable to repay for an applicant with no income.
