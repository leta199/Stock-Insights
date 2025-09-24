# Stock-Insights-
## ABOUT THIS PROJECT   
For this project I aim to utilise Python packages such as matplotlib in order to track prices of stcoks available  through the yfinance API wrapper. This allows me to crrate time-series graph showing historic prices of these stocks.

## HOW IT'S MADE   
Languages used: Python verion (3.9.0 64-bit)   
Packages and modules: pandas, yfinance, matplotlib  
IDE: Jupyter notebook, Visual Studio Code 

## METHODS AND TECHNIQUES 
**Data extraction**   
Utilised the .ticker() method to extract information on AMD stock data. 
Used the .info method to get historic information on the stock as dictionary.   
Turned history stock prices data into dataframe with .history().  

**Data preparation**   
Chnaged the index od the dataframe into standard Python index with .reset_index().  

**Visualisation**  
Plotted Historic stock prices over time.

## PROJECT STRUCTURE   
[Stock Insights](https://github.com/leta199/Stock-Tracker-)‐/   
├── [Stock Tracker](https://github.com/leta199/Stock-Tracker-/blob/main/Stock_tracker.ipynb)/    
└── [ReadME](https://github.com/leta199/Stock-Tracker-/blob/main/README.md)/

## KEY FINDINGS AND INSIGHTS  
1) The price of AMD stock has grown exponentially in the last 10 years.

## FURTHER EXPANSIONS  
I would  like to incorporate economic influences on stock prices like inflation and interest rates to investigate how these have affcted AMD and other companies. 
In time as I grow better in Python, I wish to implement machine learning models to predict future stock prices to help in investment decisons possibly incorporating numeric features like interest rates and competitor stock prices to make my predictions more accurate. 

This would be very useful in the following fields: 

1) Finance and invetsment- quantitaive strategies to increase rerurn on onvestment.
2) Corporate finance- understanding market sentiment.
3) Goveernance and policy- allows regulatory bodies to keep track of the best performing companies and implement lasws to sterngthen industry.
4) Economic research- in event studeis to realise how stock prices are affetced by news and events and predict how future evenst will affect stocks.

## AUTHORS  
[leta199](https://github.com/leta199)
