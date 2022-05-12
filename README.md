
# Project 2: Predicting Housing Prices in Ames, Iowa


This project aims to assist property agents in Ames, Iowa to provide better advice to their clients who would like to buy/sell housing properties in the city. 

After an in-depth analysis of the a comprehensive datasets on houses in Ames/Iowa sold between 2006 and 2010, I tested several linear regression models to seek out the best model that could predict housing prices in the city. 
The model also informs us on the best predictors of housing prices i.e. the key features of the house/environment affect housing prices. 



## Problem Statement

   We are a team of data scientists working for a real estate agency in Ames, Iowa. 

   We have been tasked to identify features that are the best predictors of housings prices in the city and successfully predict housing prices based on those features. 

   The model will benefit our real agents, by providing a real gauge of housing prices based on key features, which can they draw reference from when they are advising clients looking at buying/selling their homes.  

   Some of the questions that a property agent might have include:
  *  Q1. At what price should I advise my client to sell or buy a particular house? 
  *  Q2.What features of the house are more important in determining house price?
  *  Q3. Are there any features that my client can improve or remodel to fetch a higher price, if they intend to sell? 
    
The success of the regression models is evaluated based on their R2 (close to 1 the better) and RMSE (lower the better) scores. 
## Data Documentation

Please refer to the following page for a comprehensive documentation of the data available in the Ames housing dataset:
[Source.
](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt
)


## Summary of Analysis

The lasso regression model was the best performing model, out of other regression models that were tested.. 

The features that are most significant predictors of housing prices as as follows:

[image1](images/top20.png)


The COVID-19 pandemic generally had a negative impact on the participation rates and aggregrated scores in SAT and ACT tests, across states in the US. The mean/median of SAT/ACT participation rates and aggregated scores certainly decreased across board over the period from 2019 to 2021. 

**ACT & SAT participation during the pandemic**

When the pandemic was at its peak in 2020 and 2021, all states tightened restrictions to curb the spread of the virus. This led to many SAT/ACT testing centres to be closed or reduce their testing capacity and therefore affected the participation rates within each state. However, some states were in fact, worst off than others. Key findings as follows: 

*ACT*    
* There are 5 states that maintained 100% participation rate in ACT from 2019 to 2021 However, none of the states demonstrated year-on-year improvement in participation rates from 2019 to 2021.    
* There are 6 states that had above average participation rate in ACT in 2019, but experienced significant decline in participation rate from 2019 to 2021.
  
*SAT*
* None of the states maintained 100% participation rate in SAT from 2019 to 2021. Interestingly, one state i.e. New Mexico saw year-on-year improvement in participation rates from 2019 to 2021. 
* There are 5 states that had above average participation rate in SAT in 2019, but experienced significant decline in participation rate from 2019 to 2021.    

**ACT & SAT aggregated scores during the pandemic**

There is strong negative correlation between participation rates and aggregated scores for ACT and SAT. Therefore, it is expected that as participation rates dropped during the pandemic, aggregrated scores would generally increase. However, the experience certainly varied across states.  

*ACT Composite Score*
* None of the states maintained the same ACT composite score from 2019 to 2021. Likewise, none of the states experienced a year-on-year improvement in ACT composite score from 2019 to 2021. 
* 13 states experienced year-on-year decline in ACT composite scores from 2019 to 2021. 
* There are 5 states that had above average ACT composite score in 2019, but experienced a decline in composite score from 2019 to 2021. However, the percentage difference is small - between 0.4% to 0.8%. 
    
*SAT Total Score*
* None of the states maintained the same SAT total score from 2019 to 2021. Interestingly, 5 states experienced a year-on-year improvement in SAT total scores from 2019 to 2021.
* 9 states experienced year-on-year decline in SAT total scores from 2019 to 2021. 
* There are 5 states that had above average SAT total score in 2019, but experienced significant decline in composite score from 2019 to 2021. The percentage difference is between 1% to 8%.
   

## Conclusions & Recommendations

In 2022, more colleges are likely to reinstate the SAT/ACT requirement for enrollment applications and more testing centres will resume operations. In preparation for this, the College Board and ACT Inc. will need to re-allocate their resources for support more testing operations.  

In order to improve future participation rates in SAT and ACT, the College Board and ACT Inc. should consider allocating more resources to states that meet two criteria:

    1. Above average participation rate in pre-pandemic period i.e. 2019, and
    2. Greatest decline in participation rate from 2019 to 2021. 




**ACT Inc. should focus on the following states:**

ACT | State |Participation Rate (2019) |% Difference in participation rate (2019 to 2021) |
--- | --- | --- | --- |
1 | New Mexico |0.63|-0.63|
2 | Arizona |0.73|-0.52|
3 | Oklahoma |1.00|-0.42|
4 | Minnesota |0.95|-0.36|
5 | South Carolina|0.78|-0.35|

**College Board should focus on the following states:**

SAT | State |Participation Rate (2019)|% Difference in participation rate (2019 to 2021) |
--- | --- | --- | --- |
1 | Maine |0.99|-0.70|
2 | Oregon |0.51|-0.66|
3 | California |0.63|-0.61|
4 | Washington |0.70|-0.61|
5 | Massachusetts |0.81|-0.58|

This would allow these states to bounce back to their pre-pandemic levels faster, and will likely increase the overall participation rates in the respective tests. 
## Next Steps