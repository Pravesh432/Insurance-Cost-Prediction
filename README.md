# Insurance-Cost-Prediction
using Regression Algorithms of Machine Learning I want to determine the yearly insurance of persons.


# Problem Statement: 
###  In this dataset we're going to use information like a person's age, sex, BMI, no. of children and smoking habit to predict the price of yearly medical bills. 
###  This kind of model is useful for insurance companies to determine the yearly insurance premium for a person. 

# About the Dataset:
- The dataset consists of 8 feature columns and 1338 rows. In this dataset we want to predict on numeric value Charges output.
- So we use Regression Algorithms for this dataset.

# Steps:
- Check null Values
- ![null](https://user-images.githubusercontent.com/105968767/215262000-44dbc234-e5cc-4847-9016-d5fdf640bf2f.png)

- Check Skewness:
![skew](https://user-images.githubusercontent.com/105968767/215262027-d5427cdc-d968-4b0d-bc80-9fc471c6771b.png)

- Check Correlation
- ![corr](https://user-images.githubusercontent.com/105968767/215262118-7bb7dc71-18ec-4685-a18b-6995044a3975.png)

- After Applying Modelling Got a r2 Score:
- ![r2](https://user-images.githubusercontent.com/105968767/215262268-aa658ca8-270a-43f7-bb96-e43fd1709cee.png)

- So IN this Assumption are not fullfill so go for Polynomial then Score:
- ![ploy](https://user-images.githubusercontent.com/105968767/215262381-04152400-1e8a-4570-8491-c05cb8bdf217.png)

- Check the Overfitting Using Lasso and Ridge
- ![lasso](https://user-images.githubusercontent.com/105968767/215262503-dbda4ec0-8675-47e9-afdc-6f2ce486bd28.png)
- ![ridge](https://user-images.githubusercontent.com/105968767/215262669-e7f1fdb0-5b5b-4ea9-b115-bf0310bd32f6.png)




- 

