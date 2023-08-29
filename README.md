# Zillow_Price_Analysis_using_R
Zillow Rental Price Analysis with Hypothesis Testing Repository. Includes Data collection, Preprocessing, EDA, Hypothesis Formulation, Testing and Results

## Introduction

The COVID-19 pandemic initially caused a drop in demand for rental properties in cities like New York, leading to lower rent prices as landlords sought tenants. However, as the situation evolved and economic activities resumed, some people returned to cities, driving up demand and subsequently pushing rental prices back up. Factors like inflation and supply chain disruptions also play a role in these fluctuations. The current challenges of higher gas and grocery prices, along with inflation, further impact people's ability to afford housing costs, including rent.

## Goal

Hypothesis - The rent price drastically went down during the pandemic time due to less demand.

Using the data we collected, we are going to analyze it with every states in US and check whether the hypothesis is correct or wrong.

## Steps

1. Data Collection - Web Scraping
We scraped the data from https://www.zillow.com/research/data/, which is a big player in NY rental market

2. Data Transformation 
So, we got our hands on some data from Zillow in the form of CSV files. We wanted to dig into this data, so we used a bunch of functions from R's dplyr package, like mutate(), select(), filter(), group_by(), and summarise(). And you know what? We also got some help from the tidyr package, using functions like gather() and spread() to make our data just right for plotting. What did we pick from the data? Well, we went for the good stuff – City, State, and those median house prices. Armed with this info, we dived into exploratory data analysis (EDA) to really understand the trends and stories hidden in the numbers. Built interactive vizualizations. Also handled the missing data
  

3. Results
COVID-19 impacted rental prices in both Boston and New York. New York saw a more rapid and significant drop, starting in March 2020, compared to Boston's decline in May 2020. New York's decrease was over twice that of Boston. The recovery began in May 2021 for Boston and June 2021 for New York. By October 2021, New York's rental prices had not only rebounded but also surpassed Boston's, reflecting a strong recovery surpassing pre-COVID levels. Comparing New York apartment prices in 2018 and 2019 reveals an interesting trend – there had never been a price drop for the same month in consecutive years prior to the pandemic. The COVID-19 pandemic was the driving force behind the rental price decline in New York during 2020. Notably, rental prices tend to peak in July (Fall), while increases within a year are less pronounced during the winter months, particularly in December.
