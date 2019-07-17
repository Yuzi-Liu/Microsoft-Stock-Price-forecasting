# Microsoft-Stock-Price-forecasting
The project objective is to forecast the stock price of Microsoft at the end of 2019 based on contextual factors.

I chose to use two datasets; one is from 1/31/2001 to 2/28/2019; the other is from 3/31/1986 to 2/28/2019. There are reasons for using these time ranges: 
a. The market structure has undertaken significant changes since Microsoft’s IPO on 3/13/1986. 
b. Microsoft has become a component of DOW 30 since November 1999.

Alteryx and Tableau are the software I used for this project. The independent variables are S&P 500 index, NASDAQ index, DOW 30 index, revenue of Microsoft, Apple, and IBM, Real GDP growth rate, interest rate (Federal Funds Rate), consumer sentiment index, market cycle, and economic cycle, with some of the variable transformations (Log, Quadratic).

After Conducting Feature engineering to determine 10+ variables, I created cycle replication, developed an ensemble forecast model based on 7 different time series models (Random Forest, Stepwise Regression, etc.) to predict the year-end Microsoft stock price using Alteryx 

I also built a What-if interactive dashboard on Tableau to evaluate different scenarios on Microsoft's stock price.
