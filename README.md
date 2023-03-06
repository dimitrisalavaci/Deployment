# Mini-project IV

### [Assignment](assignment.md)

## Project/Goals

- The main goal is to study the data given, clean/add/replace data that is needed, create a model that will be able to predict whether or not someone applying for a loan will be accepted or not given certain criteria.

## Hypothesis

Which applicants are more likely to get a loan?

*Possible Factors:

1. Applicants having a credit history 
2. Applicants with higher applicant and co-applicant incomes
3. Applicants with higher education level
4. Properties in urban areas with high growth perspectives
5. Applicants that apply for a lower loan amount
6. Applicants that are married
7. Applicants with 0 dependents

## EDA 

- Check to see if there are any missing values in columns
- Check categorical values & frequency in nominal variables
- Plot graphs to check data from a visual standpoint
- Use boxplot to identify outliers(if there are any)
- Add any missing values 
- Replace any string values with numerical values
- Use log transformation to get rid of extreme values
- Combine columns(ApplicantIncome, CoapplicantIncome)


## Process

- Create hypothesis 
- Import and load dataset
- Perform EDA
- Build a model
- Use pipeline on the model 
- Deploy model onto the cloud and test it


## Results/Demo

- Created a logistic regression model
- Accurary of it was 80%
- Used GridsearchCV to try and get better results
- Accurary increased to 82%
- Slight improvement but still feel as if it isn't good enough

## Challanges 

- Had difficulties deciding which model to choose from.
- Wasn't able to test different models to see if they would give better results than my logistic regression model.
- Had difficulties creating the API through AWS and Flask, constantly getting error after error when trying to run it.


## Future Goals

- I would create and test at least 4 different models before picking the one that gave the best results.
- I would sort out the API issue earlier and have it running right away.
- As far as potential bias goes, there are a couple columns such as Gender and Education where it looks like the majority of applicants getting loans approved are Males and Graduates but if you look at the percentages of Males and Females as well as Graduates and Non Graduates, their percentages of getting accepted are almost the same. In this case it just happens that more Males and more Graduates applied for loans, compared to Females and Non Graduates.