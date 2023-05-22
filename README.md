# ReCell-Project
Created a tool that estimates or predicts the future normalized used price of used phones (Adj. R-squared ~ 0.84) which can be used to identify the best models to optimize profit and turnover
Examined over 3,400 phones and 34 phone brands released between 2013 and 2020

## Code and Resources
**Python Version:** 8.2.0
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, statsmodels

## Data Cleaning
The dataset was mostly clean for modelling. Certain features were engineered into the dataset. These include:
- Creation of column `years_since_release` from the `release_year` column
- I considered the year of data collection, 2021, as the baseline.
- `release_year` column was dropped
There were missing values that treated

## Exploratory Data Analysis
I examined the data distributions and value counts for various features. Some of the insightful plots are highlighted below.
<left><img src="https://github.com/Ariyo347/ReCell-Project/assets/113588909/eb82d45e-de26-474e-9fd1-a662a3acddb0" width="400" height="400"></left>
<right><img src="https://github.com/Ariyo347/ReCell-Project/assets/113588909/aae3010b-ce48-4b68-9982-3797e9c1b9bd" width="400" height="400"></right>

<center><img src="https://github.com/Ariyo347/ReCell-Project/assets/113588909/2d722ed6-e45d-4cf5-82a9-865c00068fce" width="800" height="400"></center>

## Model Building 
