# Effect-of-General-Elections-on-the-Correlations-of-Returns-of-the-Financial-Products
Effect of General Elections on the Correlations of Returns of the Financial Products- WorldQuant Capstone Project 

This is a codebase of the capstone Project Titled - "Effect-of-General-Elections-on-the-Correlations-of-Returns-of-the-Financial-Products" submitted to WorldQuant University MScFE Program by Ravishankar Umashankar Sharma, Michael Owusu Agyebeng, Kunwar Kuldeep Singh.

This paper aims to analyze the impact of elections on financial market data and behavior. Generally, elections have a significant impact on the economic, fiscal, and budgetary policies of a country. The performance of the financial market is influenced by political events, as far as we understand, and there is research published by many researchers to attest to that.

For this analysis the daily returns of four financial products were chosen viz. Nifty (Equity Index of India’s leading Stock Exchange NSE), Gold, Bond Yield (10-year Gsec yield of Indian Government Bond) and FX (USDINR). The data from the most recent five Lok Sabha election periods, namely the 14th, 15th, 16th, 17th, and 18th, has been considered. We categorized the data into 365 day pre & post polling, 180 day pre & post polling and 90 day pre & post polling. We used statistical tests to check the significance of Variance, Covariance and Correlation among the product set for each election period.

Based on our Election Phase 17 data, we may deduce that the behavior of Bond Yield and Gold Price correlations with other products may alter dramatically during the post-polling period. However, if we examine the election period, we don't see any definitive results or patterns in the financial data set.


We will be testing the significance of variance, covariance and correlation among the financial products. We will use the following statistical tests to ascertain our hypothesis.

1. **Levene's Test for equality of variance**
Levene’s Test for equality of variance is done to check the significant differences between two
data sets. The significance level we will use is 0.05. The null hypothesis is that the variance across
the two groups is the same. If the p-value is less than the significance level, we shall reject the null hypothesis.
Null hypothesis (H0) = The variance across the two groups shall be the same (σ2 = σ2 =
σ2 = σ2 )
H0: The variance of returns for Bond Yield, Equity Index, FX, and Gold are equal between the Pre-Polling Period and the Polling Period.
H0: The variance of returns for Bond Yield, Equity Index, FX, and Gold are equal between the Pre-Polling Period and the Post-Polling Period.
Alternative Hypothesis (H1): At least one group has a variance different from the others.

2. **Box’s M Test for equality of covariance matrix**
Box’s M test is a multivariate statistical test which is used to understand the equality of covariance matrices. The significance level we shall be using is 0.05. The null hypothesis will be that the covariance across the two groups shall be the same. If the p-value is less than the significance level, we shall reject the null hypothesis.
Null hypothesis (H0) = The covariance across the two groups shall be the same (∑1 = ∑2 =
∑3 = ∑k)
H0: The covariance of returns for Bond Yield, Equity Index, FX, and Gold are equal between the Pre-Polling Period and the Polling Period.
H0: The covariance of returns for Bond Yield, Equity Index, FX, and Gold are equal between the Pre-Polling Period and the Post-Polling Period.
Alternative Hypothesis (H1): At least one group has a covariance different from the others.

**3. Fisher’s Z test for Correlation matrix**
Fisher’s z-test is used to check if there is any significant difference between two correlations. The significance level we shall be using is 0.05. The null hypothesis will be that the correlation across the two groups shall be the same. If the p-value is less than the significance level, we shall reject the null hypothesis.
Null hypothesis (H0) = The correlations between the variables shall be the same (ρ1 = ρ2)
H0: The correlation coefficients between Bond Yield and Gold Price, Bond Yield and USD, Equity Index and Bond Yield, Equity Index and Gold Price, Equity Index and USD, and USD and Gold Price are equal between the Pre-Polling Period and the Polling Period.
H0: The correlation coefficients between Bond Yield and Gold Price, Bond Yield and USD, Equity Index and Bond Yield, Equity Index and Gold Price, Equity Index and USD, and USD and Gold Price are equal between the Pre-Polling Period and the Post-Polling Period.
Alternative Hypothesis (H1): The correlations between the variables shall not be the same
(ρ1 ≠ ρ2).

**Methodology**
We extracted the data from websites of investing.com, World Gold Council, Reserve Bank of India and Wikipedia for the election dates. These data are freely accessible by the users.

**Data Collection**
1. Equity Index
NSE’s Nifty is selected as the Equity Index. 
Source : https://in.investing.com/indices/s-p-cnx-nifty-historical-data Date of Access : 7th July 2024

2. Gold
We have used the spot price from the World Gold Council. We have alternate thoughts of using the futures price of Gold. However, the futures price would include the carrying cost which may influence the price of the gold. Further, we had thought of using the gold price denominated in USD. But this would include the exchange rate. Due to this we ended up using the spot price available from the World Gold Council. The prices are in Indian rupee per troy ounce.
Source : https://www.gold.org/goldhub/data/gold-prices Date of Access : 7th July 2024

3. FX (USDINR)
The FX Rate which we shall be using is USDINR. USD being the reserve currency and highly acceptable in most of the transactions we chose USD exchange rate for our analysis.
Source : https://www.rbi.org.in/scripts/ReferenceRateArchive.aspx Date of Access : 7th July 2024

4. Bond Yield
The Bond yield of any country helps in figuring out the creditworthiness and repayment capability of the country. During the polling period, there might be some change in the Bond yield which we shall be analyzing. We have used the used 10 year Indian Government Security yield.
Source : https://in.investing.com/rates-bonds/india-10-year-bond-yield-historical-data Date of Access : 7th July 2024

**Election period**
Election Phase 14th - 20 April 2004 to 13 May 2004
Election Phase 15th- 16 April 2009 to 16 May 2009
Election Phase 16th -7 April 2014 to 16 May 2014
Election Phase 17th -11 April 2019 to 23 May 2019
Election Phase 18th- 19 April 2024 to 4 June 2024


