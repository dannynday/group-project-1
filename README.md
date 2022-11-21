# Dashing through Crypto Snow - Group 1 Project
### By: Ethan, Danny and Yen
## Rough Breakdown of tasks:
* Come up with an idea - Danny
* Find a new, relevant library - Yen
* Create a rough draft of code - Ethan
* Import project-specific data - Yen
* Clean up code so it is working - Danny & Yen
* Create a second notebook with logic and reasoning - Ethan
* Create a README.md file that fully captures the focus of our project - Ethan & Yen
* Create a Google Slides presentation - Danny, Ethan, & Yen

## Step 0 - Start with THE QUESTION(s).
### What is the problem that you want to solve?
* Can we outperform the S&P 500 with our strategy of utilizing more volatile assets?

* What is the our strategy performance over the past year?

* Is it always better to buy more volatile assets? 

### What is the trend you want to highlight?
Higher volatility assets provide a better return on investment than assets with lower volatility. 

### What are the insights you look to uncover?
We are expecting a better performance from the volatile assets. In addition, we will be able to identify what makes an asset profitable with high probability of returns over time.

## Step 1 - Create a Jupyter Notebook #1, explaining how you are GETTING THE DATA TOGETHER:
We took the following steps to compose the DashingCryptoSnow.ipynb Notebook 1: 
* Identified assets (BTC, ETH, TRX, TSLA, and GME) to benchmark with S&P 500
* Researched and selected a FinTech Python Library (Quantstat) to assist with our analysis
* Utilized Alpaca Markets API to retrieve the data by using the get function
* Scrubbed the data sets by using Pandas dropna(), drop column, pct_change calculation, etc.  
* Generated data visualizations using HvPlot, Seaborn, and QuantStats library.
* Double checked our work with QuantStats

Here are some examples of the data visualizations using HvPlot, Seaborn, and Quantstats: 

![SharpeRatios](../Image/SharpeRatiosAll.png)
* Here we utilized HvPlot to determine the standing of our assets, and whether they are worth their inherent risk or not. 

![CorrelationMap](../Image/CorrelationHeatMap.png)
* Here we see that the cryptocurrencies have major correlation to one another, but everything else is faily decorrelated. 

![SPY%s](../Image/SPYMonthly.png)
![GME%s](../Image/GMEMonthly.png)
![TRX%s](../Image/TRXMonthly.png)
* We were curious to see more specifically what the correlation was and if that was to impact our hypothesis at all. When you put all three of these side by side it seems like they somewhat do go up and down together at least on a monthly basis. So that supported our hypothesis that we will outperform the S&P 500 since our assets go up easier than SPY. These pictures are courteous of QuantStats, one of the many things you can do with this library. 

## Step 2 - Create a Jupyter Notebook #2, which details your DATA ANALYSIS.
### Can we outperform the S&P 500 with our strategy of utilizing more volatile assets?
* First, we prove the assets that we are buying are more volatile than the S&P 500:

![STD](../Image/STDAll.png)
* This chart represents the standard deviation of returns for each of our assets. SPY has the least percentage moves compared to the rest.

![VolatilityAll](../Image/VolatilityBoth.png)
* This chart shows the volatility of our assets based on a year of trading. Stocks only have 253 trading days a year, while crypto has all 365 days, which is why they are seperate lines.

* Now that we have proven our assets are indeed fitting of the self-imposed requirements, we can focus on how our volatile assets do in comparison to the SPY.

![DailyReturnBoxAll](../Image/DailyBoxPlotAll.png)

* As seen in the Daily Return Box plot, all of our chosen assets have greater ranges than the SPY to both the upside and downside. We should be able to outperform the SPY based on this chart so long as markets are expanding and not contracting.

### How would our strategy have done in the past year?

![LogReturns](../Image/LogReturnAll.png)
* We can see here that everything on a braod, log scale ended up at around the same spot of return on investment over a year, even though we can see some assets were much higher or lower at some point. 

![CumulativeReturnsFull](../Image/Total_CReturns.png)

* Our strategy would not have done as well as we would have hoped after backtesting over a year's worth of data. As you can see from our charts, none of our assets outperformed the SPY over the last year. Amdist the chaos of the market, the durable and trustworthy SPY showcased its resilliance this year. 

### Is it always better to buy higher volatility assets? 

![SPYTRXDrawdown](../Image/SPY_TRX_drawdown.png)
* The yellow line represents TRX's highest daily drawdowns and the green line corresponds with it, showing the maximum point reached. The blue and red lines represents SPY in the same manner, respectively. This graph tells us that it is not always better to buy more volatile assets because the more volatile asset (TRX) has less returns this year than the less volatile asset (SPY) and the S&P kept its gains longer than Tron. 

![SPYBench](../Image/SPYBenchmark.png)
* Here you can see SPY is about -15% returns YTD. This is what we are striving to beat.

![TSLAR](../Image/TSLA_return.png)
* This is TSLA's cumulative returns, about -50%. All of our assets YTD are actuallly down 50% or more and the SPY is only down 15%. 

According to our findings, it is not always better to buy the more volatile assets. When we sample data from the past year, we can see that volatile assets have greater exposure to the down side than the S&P500. In the past year, many economists would classify risk-on assets as being in a bear market. One could conclude that when markets are in turmoil, assets that can move more quickly will move more quickly to the down side than less volatile assets. This is due to the available liquidity. The S&P500 is one of the most traded and widely available assets in the world while TRX is not well-known and only available certain places. This leads to S&P500 having a lot of trust and TRX not so much, people with lots of money feel comfortable putting and most importantly keeping large sums of money into very trusty and very liquid assets. Since S&P500 has more liquidity than TRX, it takes billions of more dollars to push the price down 60% in a day where TRX it could only be millions of dollars. You have some of the largest corporations like Vanguard and BlackRock offering S&P 500 ETF versus cryptic internet addresses offering TRX through (de)centralized exchanges. 

In essence, we had a good idea on what would allow us to outperform the SPY Benchmark, however due to current state of markets and recent turmoil, our strategy backfired. Outperforming the SPY means taking on extra risk in order to do so. We wanted to pick assets with lower liquidity than the SPY so that way when the markets are going up, our assets require less capital to move than the S&P 500. This thought-process however, applies in both directions. In accordance with our findings, our more volatile assets moved to the downside faster and easier than the SPY. Given the past year and its data, it would have simply been best to stay in cash and rebuy in lower or to allocate more of a percentage of our portfolio to less risky assets like the SPY (if we were possibly worried about missing a future buying opportunity). We created a portfolio to outperform the SPY, however over the past year, like many other hedgefunds and portfolio managers, we did not.