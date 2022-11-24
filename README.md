# Cohort analysis for retail e-store

## Tech Stack
Python / Pandas / Matplotlib / Seaborn / Jupiter Notebook

The main analysis is done in the Jupiter Notebook file [LTV_analysis.ipynb](https://github.com/IrinaPukhlova/LTV/blob/main/LTV_analysis.ipynb)

## Goal
Evaluate the LTV of clients groups who were attracted in different years, and choose a model for attracting and working with clients, which gives both more Profit and LTV (all 4 years used different models to attract and retain clients).

## Metrics and type of analysis
To solve this task, I will use cohort analysis and the LTV (Lifetime Value) metric.

## What is LTV?
LTV (Lifetime Value) is the gross profit that the average user will make over the lifetime of the product.

LTV must be calculated:

- Based on Gross Profit, not Revenue
- Using cohort analysis

## Definition for analysis in this case

<b> Customer action </b>: purchase by Order Date

<b> Cohort size  </b>: year

<b> Reporting period  </b>: 4 years, from 2014 to 2017

<b> Key metrics  </b>: LTV (which is calculated on the basis of Profit, not Revenue, in the entire existence of the cohort)

## Findings

- In 2015 the store clearly changed its policy for attracting new customers compared to 2014 -> a decrease in the number of new customers by almost 80%. But as we can see from the LTV indicator, the quality of each new customer attracted became better (growth LTV from 83.27 to 104.63)


- in 2016 new customers in the first year of purchases LTV is even better = 155.69, and in 2017 it is the highest = 164.2


- The 2016 cohort for the second year of purchases shows a better LTV than the 2014 cohort for the fourth year of purchases -> that is, the store managed to find channels to attract new customers that yield high returns per customer.

<b> BUT </b>
- At the same time, we see a decrease in total Profit with an increase in LTV in each new cohort because the store has greatly reduced the flow of new customers, and this has reduced the total Profit (although it has improved LTV)


## Conclusion

The store should not only focus on the quality of the flow of new customers (i.e. high LTV), but also the number of new customers -> it is worth trying new channels to attract more customers
