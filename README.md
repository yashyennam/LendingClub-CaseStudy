# Lending club casestudy

Identify risky loan applicants, so that such loans can be reduced to cut the amount of credit loss.Understand the driving factors (or driver variables) behind loan default.

## Table of Contents
* [Problem statement](#problem-statement)
* [Decision Risks](#decision-risks)
* [Analysis approach](#analysis-approach)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)


<!-- You can include any other section that is pertinent to your problem -->
## Problem Statement
 A consumer finance company specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile.
 
 The data given is given for past loan applicants whose loan was approved and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

## Decision Risks

Two types of risks are associated with bank decision.
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company. 
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Analysis Approach

1. Exploratory data analysis on the data set.      
2. Data Understanding:

    Address Quality issues
    Handle outliers
3. Data cleaning and manipulation.
 
    Format the data based on data types like date, float, int.   
    Derive columns based on the existing columns. 
4. Data analysis

    Univariate analysis
    Bivaraiate analysis
5. Conclusions

    Conclusion based on patterns and drivers

## Conclusions
- Driver 1 : Default percentage

    Lending club performance is increasing by every year, with higher number of fully paid loans by every passing year.
    Approx. 14% of lenders have not paid back the loan
- Driver 2: Seasonality

    The trend varies based on the month, it is higher in winters compared to summers.
    Recommendation: Can increase offers during summer to attract more volumes in months with less demand.
- Driver 3: States

    Top 5 States with maximum Charged off Rates : Nevada,Alaska,Tennessee,South Dakota,Hawaii
    Top 5 States with Minimum Charged off Rates : Wyoming,Mississippi,District of Columbia,Kansas,Delaware
    Recommendation: Make a stringent verification/Higher Interest rates to States with higher default rates and more offers/Discounts to states with lower charged off rates
- Driver 4: Purpose / Loan category

    Small Business tends to make largest category of loan which are charged off
    Vacation is tends to make least category of loan which are charged off.
- Driver 5: Public record bankruptcies

    When there is more record of bankruptcies, more likely the loan will be defaulted.
- Driver 6:  Percentage of defaulters vs home ownership
    
    When the customer owns/rents home he is less likely to default.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.0
- pandas - version 2.0
- matplotlib - version 3.0
- plotly - version 4.3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is done for lending club case study.
- Thanks to the course in Coursera (https://www.coursera.org/learn/credit-risk-management/home/welcome) for helping in understanding the credit framework and to stackoverflow in helping to resolve the technical queries.



## Contact
Created by [@yashyennam][@idhaya-r] - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
