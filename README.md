# Stock-analysis

## Overview of Project
In this week challenge, we were given a significant ammount of data regarding wall street stocks. We are trying to help our friend steve. Steve was helping his parents invest in stocks, his parents were really excited in green energy, so they decided to invest in companies that were related to green energy. Steve was a bit concern with their performance, but analysing the data manually seemed a bit uneficient. We decided to help him and run analysis on the stock performances to present them and identify them in a more simple way. 

Steve is looking to analyse all the stocks availabe, and create a more complete research for his parents. This of course presents a problem to the macro we have developed. While it does work and completes every action required, the run-time is pretty uneficient. So, using the macro as it is with a larger dataset might take it more time to complete all the task. For this we are charged with refactoring the code in order to make more efficient and run in less time. 

For this project we used and learned VBA (Visual Basic for Applications). With the help of this tool, we were able to automatize the analysis and calculus needed to analyze each stock. Not only that, but we also made sure to refactore the code and garantee a more efficient solution, capable of being used in larger datasets containing more than 12 stocks.

## Results

### Stock Performance
To identify a stock performance we are going to calculate the return. For this we needed to identify the first and last closing price the stock had in that year. Fortunatly for us, the dataset was organized by ticker and by date. This made the work of finding the firs and last price easier, because we only needed to look up the first time the ticker appeared and the last time it did, to then compare each closing price. To do this, we created 2 *If-Conditionals*. 

**Add Image of Code**

Now that we had all the numbers needed to calculate the return, we needed to made the calculations. The formula to get the return was *Return=(ClosingPrince/StartingPrice)-1*

In 2017, most of the stocks performed pretty well. Most of them have positive returns, and some even manage to almost triplicate their value, like SEDG or DQ with a return of 184.5% and 199.4%.

![Stock_Performance_in_2017](Resources/Results/VBA_Results_2017.png)

This seemed great and like an obvious investment opportunity. We can now understand why steve parents invested in DQ stocks, with their 199.4% return. Sadly, the year 2018 was not very friendly for them. Most of the stocks gave negative returns. Only two out of the twelve stocks had a positive return.

![Stock_Performance_in_2018](Resources/Results/VBA_Results_2018.png)

Seeing how the stocks perfomed, it is not a surprise that steve wanted to do a broader research and investigate more options. Although this decrease might be due to certain news regarding green energies or anomalies, it is better to start seeing other options. We need to expand the data set to include more stocks and see how well are other stocks performing and identify those that are worth investing. In order to scale up the dataset, we need to refactor our code and make sure it runs more efficiently. 

### Code Performance


## Summary

## Extras
