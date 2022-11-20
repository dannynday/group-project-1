# Dashing through Crypto Snow - Group 1 Project
### By: Ethan, Danny and Yen

## Step 0 - Start with THE QUESTION(s).
### What is the problem that you want to solve?
* Can we outperform the S&P 500 with our strategy of utilizing more volatile assets?

* What is the our strategy performance over the past year?

* Is it always better to buy more volatile assets? 

### What is the trend you want to highlight?
* Our strategy can outperform the S&P 500 regardless of market conditions. 

### What are the insights you look to uncover?
* We are expecting the higher performance from the volatile assets in any market conditions. In addition, we will be able to identify good assets with high probability overtime and low risk than S&P500.

## Step 1 - Create a Jupyter Notebook #1, explaining how you are GETTING THE DATA TOGETHER:
We took the following steps to compose the DashingCryptoSnow.ipynb Notebook 1: 
* Identified assets (BTC, ETH, TRX, TSLA, and GME) to benchmark with S&P 500
* Researched and selected a FinTech Python Library (Quantstat) to assist with our analysis
* Utilized Alpaca Markets API to retrieve the data by using the get function
* Scrubbed the data sets by using Pandas dropna(), drop column, pct_change calculation, etc.  
* Generated data visualizations using HvPlot, Seaborn, and Quantstat library.

Here are some examples of the data visualizations using HvPlot, Seaborn, and Quantstat: 

* Cumulative Returns
![CumulativeReturns](https://github.com/dannynday/group-project-1/blob/main/Image/CumulativeReturns.GIF)

* Daily Return Box: 
![DailyReturnBox](https://github.com/dannynday/group-project-1/blob/main/Image/DailyReturnBox.GIF)

* S&P 500 Max Draw Down
![MaxDrawDown_SPY](https://github.com/dannynday/group-project-1/blob/main/Image/MaxDrawDown_SPY.GIF)

* SPY Monthly Return:
![SPY_Monthly_Return](https:)

* Qantstat TRX Cumulative Return:
![QS_TRX_CReturns](https://github.com/dannynday/group-project-1/blob/main/Image/SPY_Monthly_return.GIF)

* Qantstat Draw Down
![QS_TRX_Drawdown](https://github.com/dannynday/group-project-1/blob/main/Image/QS_TRX_Drawdown.GIF)

* Qantstat Monthly Return
![QS_TRX_Monthly](https://github.com/dannynday/group-project-1/blob/main/Image/QS_TRX_Monthly.GIF)

* Qantstat  Return Quantiles
![QS_TRX_ReturnQuantiles](https://github.com/dannynday/group-project-1/blob/main/Image/QS_TRX_ReturnQuantiles.GIF)


## Step 2 - Create a Jupyter Notebook #2, which details your DATA ANALYSIS.
### Can we outperform the S&P 500 with our strategy of utilizing more volatile assets?
* First, we prove the assets that we are buying are more volatile than the S&P 500:

![Volatility](https://github.com/dannynday/group-project-1/blob/main/Image/Volatility.GIF)

![Correlation](https://github.com/dannynday/group-project-1/blob/main/Image/correlation.GIF)

* Now that we have proven our assets are indeed fitting of the self-imposed requirements, we can focus on how our volatile assets do in comparison to the SPY.

![DailyReturnBox](https://github.com/dannynday/group-project-1/blob/main/Image/DailyReturnBox.GIF)

* As seen in the Daily Return Box plot, all of our chosen assets have greater ranges than the SPY to both the upside and downside. We should be able to outperform the SPY based on this chart so long as markets are expanding and not contracting.

### How would our strategy have done in the past year?

![CumulativeReturns](https://github.com/dannynday/group-project-1/blob/main/Image/CumulativeReturns.GIF)

![SharpeRatio](https://github.com/dannynday/group-project-1/blob/main/Image/sharpe_ratio.GIF)

*Our strategy would not have done as well as we would have hoped after backtesting over a year's worth of data. As you can see from our chart, one out of the four assets we held had greater cumulative returns than the S&P 500. $TRX, Tron cryptocurrency coin, was a massive outlier in our findings, as it was the only asset to outperform the S&P 500, thus the other assets, and by a large margin. On Apirl 16, 2021, $TRX was outperforming SPY by 96.6%. The risk-reward indicator or sharpe ratio's demonstrate to us that even though our assets have not been performing the best, they are still good bets. Three out of our five assets have higher sharpe ratios than the SPY. Sharpe ratios is a great indicator to determine whether an asset's volatility is worth it or not.

### Is it always better to buy higher volatility assets? 

![TRXDrawdown](https://github.com/dannynday/group-project-1/blob/main/Image/TRX%20Drawdown.GIF)

![MaxDrawDown_SPY](https://github.com/dannynday/group-project-1/blob/main/Image/MaxDrawDown_SPY.GIF)

According to our findings, it is not always better to buy the more volatile assets. When we sample data from the past year, we can see that volatile assets have greater exposure to the down side than the S&P500. In the past year, many economists would classify risk-on assets as being in a bear market. One could conclude that when markets are in turmoil, assets that can move more quickly will move more quickly to the down side than less volatile assets. This is due to the available liqudity. The S&P500 is one of the most traded and widely available assets in the world while TRX is not well-known and only available certain places. This leads to S&P500 having a lot of trust and TRX not so much, people with lots of money feel comfortable putting large sums of money into very trusty and very liquid assets. Since S&P500 has more liquidity than TRX, it takes billions of more dollars to push the price down 60% in a day where TRX it could only be millions of dollars. You have some of the largest banks like Vanguard and BlackRock offering S&P500 versus cryptic internet addresses offering TRX through decentralized exchanges. 

* dive deep into your analysis.
* confirm or infirm your hypotheses.
* deliver your conclusions.


Provide a short description of what you found and any relevant plots under each heading.