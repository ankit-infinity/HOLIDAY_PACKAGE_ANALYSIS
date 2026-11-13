# HOLIDAY PACKAGE PURCHASE PREDICTION AND CUSTOMER ANALYTICS


## REPORT LINK :

https://app.powerbi.com/view?r=eyJrIjoiMGMyMDBlNDQtNGQyMC00NGVjLWIwNTktZjM2OTJmMjNmOTYyIiwidCI6ImFhODNiNGE3LTI4ZDItNDVhOC1iMmNlLTIwODIxMTkyMmE4MSJ9

## OVERVIEW:

This project focuses on analysing customer purchasing behaviour and predicting the likelihood of holiday package purchases for a tourism company using Business Intelligence and Machine Learning techniques.

The objective is to help the company understand its customers, identify valuable customer segments, and predict which customers are more likely to purchase a holiday package. The analysis explores customer demographics, income, occupation, travel preferences, and sales pitch characteristics to uncover patterns associated with purchasing decisions.

The project follows an end-to-end analytical approach, combining exploratory data analysis, customer segmentation, interactive dashboard development, and predictive modelling.

## KEY COMPONENTS:

1. Exploratory Data Analysis (EDA)
Analyse customer demographics, purchasing behaviour, income distribution, travel patterns, and relationships between customer attributes and package purchases.

2. Customer Segmentation
Identify meaningful customer groups, including young professionals, high-income customers, family travellers, frequent travellers, premium prospects, and travel-ready customers. Compare their purchase conversion rates to identify potential marketing opportunities.

3. Business Intelligence with Power BI
Develop interactive dashboards to monitor customer demographics, purchase conversion, segment performance, package presentation patterns, and marketing opportunities.

4. Machine Learning – Purchase Prediction
Develop and compare supervised binary classification algorithms to predict whether a customer will purchase a holiday package (ProdTaken). Evaluate model performance using classification metrics such as precision, recall, F1-score, confusion matrix, and ROC-AUC.

5. Business Insights & Recommendations
Translate analytical findings and model predictions into actionable recommendations for customer targeting, marketing campaign optimisation, and sales resource allocation.

## DATASET:

Important variables:

- ProdTaken: Whether the customer purchased the holiday package (1 = Yes, 0 = No) also a target variable.
- Age: Customer age.
- MonthlyIncome: Customer monthly income.
- Occupation: Customer occupation.
- MaritalStatus: Customer marital status.
- NumberOfTrips: Number of trips taken.
- ProductPitched: Holiday package presented to the customer.
- Passport: Whether the customer has a passport.
- PitchSatisfactionScore: Customer satisfaction with the sales pitch

## BUISNESS REQUIREMENTS:

The company wants to understand:

- Identify the total number of customers and analyse their demographics based on age ,gender,martialstatus and occupation 
- Monitor the number of customers who purchased the holiday package versus those who didn't purchase.
- Categorise customers into different segments based on income,age,travel frequencyand purchasing behaviour to identify potential buyers.
- Evaluate the performance of different holiday packages (Productpitched) and identify which package generate the highest customer service.
- Analyse customer travel preference including number of trips family travel behaviour and preferred hotel property rating
- Evaluate how pitch duration, number of follwow ups, contacttype and pitch satisfaction influence customers purchasing decision .
- At last bulid predictive model for accurately predicting the prod taken.

## INSIGHTS:

- There are total 4128 customers out of which majority of the customers falls between the age group of 35-44 and male customer are more in number than female customer who are interetsed in the product,married couple are more interested in product taken freelancer are high rate of conversion regarding product interested.

- There are total 797 customer which is 19% of total customers who purchase the product where as the number of customer who didn't purchase the product stands out 3331.

-  Out of product pitched categories 'basic' package generate highest conversion rate overall whereas 'super deluxe' generate least conversion rate .

- The average number of trips stands out to be 3.30 .Individual belongs to family traveller has overall 19% conversion rate and mostly preferred property star is 3 .

-  
categories               correlation

ProdTaken                 1.000000
NumberOfFollowups         0.111560
PreferredPropertyStar     0.098704
DurationOfPitch           0.076089
PitchSatisfactionScore    0.051394
NumberOfTrips             0.019709
 
the above table is the correlation measure of different variable with the target variables (prod taken)we see that majority of the variable has positive correlation but not strongly correlated which indicate that these variable doesn't influence customer purchasing decision.

- 






