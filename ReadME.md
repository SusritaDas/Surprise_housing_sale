# Surprise_Housing_Sale_Prediction
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

# Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

# Methods Used :

1. First I imported some impotant python libraries
2. Then I loaded the data file
3. Basic checks on the datasets
4. cleaning the data by Nan values handling, missing values handling and outliers removal
5. EDA
6. Univariate bivariate multivariate analysis
7. preparing the train/test data
8. Model building - linear regression. 2 sets of model I builded by excluding features with insignificant P values.
9. r2 for 1 st Model - 78.7 %
   r2 for 2n model -  95.8 %
10. calculating ridge regression
11. Calculating Lasso regression
12. Checking the alpha value obtained from both
13. Deriving the best variables which has affect on house sale the most.

## Conclusions:

#Best alpha value for Lasso : {'alpha': 0.001}
#Best alpha value for Ridge : {'alpha': 0.1}

Upon evaluating various models, it's evident that certain features play a pivotal role in elucidating the selling price of houses:
1. MSSubClass_90 (Type of Dwelling - DUPLEX - ALL STYLES AND AGES)
2. MSSubClass_120 (1-STORY PUD - Planned Unit Development - 1946 & NEWER)
3. RoofMatl_Membran (Roof Material - Membrane)
4. MSZoning_RL (Residential with Low Density - General Zoning Classification)
5. MSZoning_FV (Floating Village Residential)
6. MSZoning_RH (Residential High Density)
7. MSZoning_RM (Residential Medium Density)
8. Condition2_PosA (Adjacent to Positive Off-Site Feature)
9. RoofMatl_WdShngl (Roof Material - Wood Shingles)
10. Neighborhood_NoRidg (North Ridge)
11. OverallQual (Excellent Overall Quality)
These features, ranging from dwelling types and zoning classifications to roofing materials and neighborhood designations, collectively contribute significantly to the explanation of house sale prices. Among them, 'OverallQual' specifically encapsulates the exceptional quality aspects of a property, encompassing superior craftsmanship, high-end materials, and an impressive overall aesthetic, which notably influences the property's market valuation.

## Acknowledgements:

1.Upgrade Course materials, recorded sessions
2.Upgrade live sessions
3. Upgrad Teacher - Akaashdeep Makkar
4. Upgrad Personal Coach - Mukesh Jain

##  Contacts

###### Developer : Susrita Das
###### Group : C55
###### email : susrita.das@gmail.com
###### Phone no. +91 8584097202
###### https://github.com/SusritaDas/Surprise_housing_sale


```python

```
