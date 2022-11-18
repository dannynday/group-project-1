# Dashing through Crypto Snow - Group 1 Project
###By: Ethan, Danny and Yen

## Step 0 - Start with THE QUESTION(s).
### What is the problem you want to solve?
* Can we outperform the SP500 when we buy more volatily assets?
* How would our strategy have done in the past year?
* Is it always better to buy higher volatility assets? 
### What is the trend you want to highlight?
* During the downturn, it is better to buy less volatile assets. 
### What are the insights you look to uncover?
* We are looking to find if volatile assets would outperform during market downturn and upswing and
* identify good assets with high probability overtime and low risk than SP500.

## Step 1 - Create a Jupyter Notebook #1, explaining how you are GETTING THE DATA TOGETHER:
* Identified assets to benchmark with SPY 500 and researched a Quantstat library to help us with our analaysis.
* Utilized the Alpaca Markets API to retrieive the data by using the get function and cleaned up the data sets by using Pandas, dropna(), drop column, pct_change calculation, etc.  
* Generated data visualizations using HvPlot, seaborn, and Quantstat.

* Save PNG images of the visualizations you find relevant to answer THE QUESTION.


## Step 2 - Create a Jupyter Notebook #2, which details your DATA ANALYSIS.
### Can we outperform the S&P 500 by buying cryptos that are more volatile than it?
* First, to prove the assets that we are buying are more volatile than the S&P:
![volality](https:)
* Now that we have proven our assets are indeed fitting of the self-imposed requirements, we can focus on how our volatile assets do in comparison to the SPY.

* As seen in the Daily Return Box plot, all of our chosen assets have greater ranges than the SPY to both the upside and downside. We should be able to outperform the SPY based on this chart so long as markets are expanding and not contracting.

### How would our strategy have done in the past year?
*Our strategy would not have done as well as we would have hoped after backtesting over a year's worth of data. As you can see from our chart, only one of the four assets we held had greater cumulative returns than the SPY. $TRX, Tron the cryptocurrency coin, was a massive outlier in our findings, as it was the only asset to outperform the SPY, thus the other assets, and by a large margin. On 4/16/21, $TRX was outperforming SPY by 96.6%. The risk-reward indicator or sharpe ratio's demonstrate to us that even though our assets have not been performing the best, they are still good bets. Three out of our five assets have higher sharpe ratios than the SPY. Sharpe ratios is a great indicator to determine whether an asset's volatility is worth it or not.

### Is it always better to buy higher volatility assets? 
According to our findings, it is not always better to buy the more volatile asset. When we sample data from the past year, we see our more volatile assets have greater exposure to the down side than the SPY. In the past year, many economists would classify risk-on assets as being in a bear market. One could conclude that when markets are in turmoil, assets that can move more quickly will move more quickly to the down side than less volatile assets. This has to due with available liqudity. The SPY is one of the most traded and widely available assets in the world while TRX is not well-known and only available certain places. This leads to SPY having a lot of trust and TRX not so much, people with lots of money feel comfortable putting large sums of money into very trusty and very liquid assets. Since SPY is so much more liquid than TRX, it takes billions of more dollars to push the price down 60% in a day where TRX it could only be millions of dollars. You have some of the largest banks like Vanguard and BlackRock offering SPY versus cryptic internet addresses offering TRX.

* dive deep into your analysis.
* confirm or infirm your hypotheses.
* deliver your conclusions.


Provide a short description of what you found and any relevant plots under each heading.