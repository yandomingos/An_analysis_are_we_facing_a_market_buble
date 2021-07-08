
![](./Images/bubble.jpeg)

# An analysis of the stock market - are we facing a market bubble? 

This project aims to analyze the stock market's current and historical data and answer to the question 'are we facing a market bubble?'. The team analyzed the gathered data via Python's packages and Data Visualization: Pandas, Numpy, Plotly.. (add more). 

The following questions were answered throughout our analysis:

Are the interest rates and economic growth showing signs of a bubble?
[Analysis of the Economic Growth(GDP) and Interest Rates](https://github.com/yandomingos/project_1/blob/main/Interest_rates_and_gdp.ipynb)

![image1](./Images/image1.png)
![image2](./Images/image2.png)
![image3](./Images/image3.png)

One of the main causes of a financial bubble is the abundance of money in the market. When long term interest rates are lowered, banks are incentivized to give more credit thorugh the landing process. This 'bubbly' process most of the time leads to the formation of a bubble in the economy.
As per shown on graph, interest rates have been lowering signifficantly and were at the lowest in 2020, it went back up at the beginning of the year, however, slowed down again mid-year. 

The slow down of th economy is one of the main indicators that the market is going to crash. As per shown on graph, 2020 showed an economic slow down because of the pandemic, however, things started picking up rapidly after with government incentives. Additionally, in comparison to the 2008 crash, the slow down was a lot more significant in 2020.
What impacts do the economic impacts on the stock markets?


[Analysis of Money Supply and GDP](https://github.com/yandomingos/project_1/blob/main/Money_Supply_ivan.ipynb)
We tried to investiage the relationship of each economic indicators with the stock market performance (S&P500) by using the panada function corr(), and we found that the money supply and inflation rate has positive correlation with the S&P500 return.  Seaborn library was utlitlzed to plot the heatmap to show the correlation matrix.

![picture](./Images/heatmap.png)

We observed that SP500 has a positive correlation with the money supply, and we will investigate further with the money supply.  By using the hvplot function, we plotted the money supply and the SP500 return.  We observe that a magnitude of 4 times of the original supply level has been injected to the economy during the pandemic.  It caused S&P500 to rise more than 68% within this period.  We can see that the money supply has direct impact on the stock market performance.  The economy is flooded with printing money and people needs to find way to invest to maintain his purchasing power.  

![picture](./Images/SP500_Performance.png)
![picture](./Images/Msupply.png)

Furthermore, a comparison between GDP and SP500 was made to see any leads of stock market bubble.  We can see that the growth rate of S&P500 has been gone up 92% while the GDP growth only went up 15% in this period.  The growth rate of S&P500 was about 6 times of the GDP one.  It raises concern about the health of the stock market with this increasing rate.  In the past, the stock market had high potential of market crashes when the growth rate for S&P500 was way above the GDP one.  We see that from the data of 2000’s DotCom and 2008’s housing bubble.  

![picture](./Images/SP500_GDP.png)

Is there Bullish sentiment in the US stock market and particularly US tech stocks?
[Analysis of Bullish sentiment in the US stock market/large US tech stocks](https://github.com/yandomingos/project_1/blob/main/bullish_sentiment_us_market.ipynb)
<img width="1992" alt="Screen Shot 2021-07-06 at 3 06 23 PM" src="https://user-images.githubusercontent.com/83512412/124678628-eabf6200-de90-11eb-8770-10853b910591.png">
The VIX volatility Index  measures market expectation of near term volatility conveyed by stock market stock options. The VIX index is also often referred to as the “fear index” because investors use the index to gauge risk, fear and stress in the market. The index is a good indicator of risk, stress and fear because when the index peaks it indicates that there are large amounts of bearish options put, and whenever the index is low in price indicates bullish sentiment among options calls. In the above Hvplot line graph I plotted the VIX index against the Wilshire 5000 total market full cap index , which is the broadest stock market index of publicly traded American corporations, and is often regarded as the best single measure of the overall U.S. equity market. The line graph which spans from 1999-2021 showed some interesting correlations between the two indexes over the last three U.S. stock market downturns. Firstly, whenever there is a downturn in the U.S. equity market there is a spike in the VIX index. Secondly, the VIX index has always been spiking  and falling in small amounts due to the human nature of investors switching between bullish and bearish often. But after 2005 the VIX index price on average leveled out from the $20’s to $10’s. It stayed that way until the financial crisis of 2008 which caused the Vix index price to spike to $80 in November 2008. It took 4 years from 2008 to 2012 for the index to level out again to its 2005 average of ranging in the $10’s - $20’s, and stayed fairly consistent in that range from late 2012 to the begging of 2020, with the Vix index price spiking to only $40 August 2015, February 2018. But after every spike it returned to its average range of the ten’s and teen’s in price, that is until the 2020 COVID-19 pandemic hit. The VIX index price reached a high of $80 in March 2020, (The same exact price spike as the height of the 2008 financial crisis) as the Wilshire index fell from an all time high of $160 to $104 in March 2020. But as the Wilshire continues to hit new all time highs of $181 in Dec 2020, the Vix index price is still ranging fairly high in $20’s. This is a worrying sign of another market crash on the rise as the VIX index price has not returned to its average price range of mid $10’s pre pandemic. It also indicates that there is still fear, stress and risk among institutions and investors as the Wilshire Index keeps breaking all time highs early on after a market crash. 
<img width="1617" alt="Screen Shot 2021-07-06 at 3 42 23 PM" src="https://user-images.githubusercontent.com/83512412/124678668-00cd2280-de91-11eb-9098-640750afcc0f.png">


![picture](./Images/image4.PNG)
![picture](./Images/image5.PNG)

[Can the market be sustainable to such a high grow environment?](https://github.com/yandomingos/project_1/blob/main/can_the_market_be_sustainable.ipynb)
We can observe price per earnings are hovering around 45, thats means an nvestor would take an average of 45 years to get a return on his investment, of course we are not considering things such as growth of sales/profits or increase margins and net income.
In addtion, the low yield returns on SP500 companies are also putting pressure on the current market, investors are getting very little returns in comparison to previous decades.

To simply put it in perpective, either investors are ok with getting verry little return on their money or the sentiment of growth in the overall sp500 index are very bullish.



### Contributors
Victor Freire, Yan D, Ivan KN Fung, Alexander McMullan
