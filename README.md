# Project-1

## Project Members
Nipun, Jeff, Exzavier

## Title
ETF Analysis

## Project Description
Our project is based upon ETFs in the Oil(OIH), U.S Energy(IYE), and Mining Sectors(XME). Our objective was to compare the ETFs past performances by analyzing their daily returns, cumulative returns, standard deviations, rolling standard deviations, exponential weighted average, sharpe ratios, and correlation. Additionally we forecasted the future performance of each ETF using a Monte Carlo simulation for 5 years of cumulative returns. We also calculated the expected portfolio returns at the 95% lower and upper confidence intervals based on initial investments of $10,000 and $17,000.

## Datasets Used
Historical stock data from all 3 ETFs pulling from an API

## Team Task Breakdown
Each team member was responsible for using alpaca to import their stock data into a dataframe and calculating the daily returns. we then combined them into a single dataframe and worked together to conduct the rest of the analysis.

## Findings
As per the data and charts that were created to display our findings, we were surprised to see how volatile these ETFs were. Although it was shown that OIH was the safest to invest it, it was still risky based on the confidence intervals and Monte Carlo simulation that we ran. You can either lose all your money or you can make nearly double of what you invest. In conclusion, if one was to invest in these ETFs, you would need to weigh more into OIH than the others to ensure some profit from your investment. Many things could have led to this data being skewed such as COVID being a part of the reason of volatility.

## Installations
To install the pandas datareader you must use 'pip install pandas-datareader' in your console. 
To install the pandas montecarlo you must use 'pip install pandas-montecarlo' in your console.
