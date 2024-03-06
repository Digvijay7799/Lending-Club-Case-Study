# Project Name : Lending Club Case Study




## Table of Contents
* [General Information](#general-information)
* [Process followed](#process-followed)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contributors](#contributors)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Case Study Information

> This Case Study is a data science project that uses the lending club data set to predict whether a loan will be defaulted or not.

### Bussiness Purpose

> This company is the largest **online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures**. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to **‘risky’** applicants is the largest source of financial loss (called credit loss). **Credit loss** is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

### Objectives

> Find the driving factors which lead to the defaulted loans which are major source of loss for the company.

### Data Set

> The data set is a csv file with the loan data for the Lending Club.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Process followed
For this analysis we have done the following :
-  We used python as our coding language
-  We loaded the loan data loan.csv
-  We modified and cleaned the data like null removal, removal of unwanted columns, character conversions etc so that its easy to use
-  We did some univariate analysis
-  We did some bivariate/multivariate analysis
-  We use histplot, countplot, scatterplot, subplot,set_palette graphs for the analysis
-  We derived some conclusions or observations



## Conclusions

-  Applicants having house_ownership as 'RENT' are likely to default
-  Applicants who use the loan to clear other debts
-  Applicants who has interest at the rate of 13-17% are likely to default
-  Applicants with employement length of 10
-  Applicants who have taken loan for purpose debt_cosolidation are likely to default
-  California (CA) has the highest number of charged-off loans, followed by Florida (FL) and New York (NY).
   It is possible that loan applications in these states may be associated with slightly higher interest rates compared to others.
-  When annual income is 50k - 100k are likely to default
-  Dti is between 12-18
-  When employee working length is 10 years are likely to default
-  When the purpose is 'debt_consolidation'
-  When loan amount is between 5k - 10k are likely to default

<!--## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis  -->

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

- Pandas - version 1.3.4
- NumPy - version 1.20.3
- Seaborn - version 0.11.2
- MatplotLib - version 3.4.3
- Plotly - version 5.7.0
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

Developed as part of the Exploratory Data Analysis Module, this case study is a requirement for the Post Graduate Program in Machine Learning and AI at IIIT, Bangalore.


## Contributors
-  Digvijay Kadam
-  Susrita Das



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
