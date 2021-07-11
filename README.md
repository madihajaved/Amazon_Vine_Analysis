# Amazon Vine Analysis

## Overview of the analysis
The aim of the project is to analyze Amazon reviews as written by Vine members. The analysis was done on US Home Improvement products database as stored on AWS and was analyzed by linking AWS RDS to postgres and using PySpark to clean and analyze the data. 

## Results 
There were 266 paid reviews from Vine members and 38,829 unpaid reviews.

The total number of five-star reviews from Vine members were 125 while from unpaid members there were 18,246 five-star reviews.

Coincidentally the percentage of five-star ratings for both paid and unpaid members is the same at 46.99%

![](https://github.com/madihajaved/Amazon_Vine_Analysis/blob/main/Vine_output.png)

## Summary 
It looks like there is no bias from paid members over unpaid members. For further analysis, the same can be done for 4-star and 1-star ratings. This would give a full picture for both positive and negative review bias. 