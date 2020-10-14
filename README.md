# Module 4 Final Project


## Introduction
We are using the zillow dataset containing the real estate prices for each zipcode for each month across the United States spanning several decades. Our goal is to find the top 3 zipcodes to invest in.

## Objectives
Narrow down the zipcodes to a smaller list of zipcodes that are the best to invest in and perform time series modeling on those zipcodes.


## The Datasets



### Problem 1: Time Series Modeling
We start with a dataframe of zipcodes across all states and we need to narrow it down. We start by grouping by states and finding the average real estate prices for each state for each month. This is followed by finding the increase in prices over the last five years for each state. We sort the states from the largest price increase to the smallest price increase and select the top three. We then create a separate dataframe for each state and sort the zipcodes within that state in a similar fashion. Finally, we select the top zipcode from each state and have our list of three, which we can use for SARIMA modeling.

### Real estate prices over time for each zipcode
AK
[Imgur](https://imgur.com/NGQBow3)

CT
[Imgur](https://imgur.com/qG8SxlI)

VT
[Imgur](https://imgur.com/nnp6ILl)


### Recomendation

Consider investing in one of the zipcodes in AK, CT, and VT. Pay attention not only to the returns but also to the volatility of prices, to achieve a better risk-return profile. The prices seem to be more consistent in Alaska.

### Conclusion
The best zipcodes to invest in are determined through both looking at a historical return on investment and the volatility of real estate prices for each zipcode. AK, CT, and VT have the largest return on investment and the zipcode located in AK has the more stable prices.























### Visualizations








### 3. Data Preparation



### 4. Modeling


### 5. Evaluation



### 6. Deployment


## Grading Rubric



## Citation

