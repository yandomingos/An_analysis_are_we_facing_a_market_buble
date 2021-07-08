
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
[Analysis of Bullish sentiment in the US stock market/large US tech stocks](https://github.com/yandomingos/project_1/blob/main/Alexander's%20Project%201%20Notebook.ipynb)
<img width="1992" alt="Screen Shot 2021-07-06 at 3 06 23 PM" src="https://user-images.githubusercontent.com/83512412/124678628-eabf6200-de90-11eb-8770-10853b910591.png">
<img width="1617" alt="Screen Shot 2021-07-06 at 3 42 23 PM" src="https://user-images.githubusercontent.com/83512412/124678668-00cd2280-de91-11eb-9098-640750afcc0f.png">


![picture](./Images/image4.PNG)
![picture](./Images/image5.PNG)


We can observe price per earnings are hovering around 45, thats means an nvestor would take an average of 45 years to get a return on his investment, of course we are not considering things such as growth of sales/profits or increase margins and net income.
In addtion, the low yield returns on SP500 companies are also putting pressure on the current market, investors are getting very little returns in comparison to previous decades.

To simply put it in perpective, either investors are ok with getting verry little return on their money or the sentiment of growth in the overall sp500 index are very bullish.



### Contributors
Victor Freire, Yan D, Ivan KN Fung, Alexander McMullan
