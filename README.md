# Stock Analysis 
Analysis of “green” stocks by comparing values for the years of 2017 and 2018. By creating a macro, the process is automated and scalable.
With the press of a button, the ticker, total volume, starting price and ending price are displayed and evaluated for profitability.

## Project Overview

## Tools

## Summary

1.	Formatted the output sheet on the “All Stocks Analysis” worksheet. The macro name is 
“AllStocksAnalysisRefactor”.
2.	We declared array for ticker as string, array for total volume as long, array for starting and ending price as double. 
3.	We initialized all the arrays to zero. 
4.	Number of rows have been calculated after activating the data worksheet.
5.	For loop has been used to go to each array element via tickerIndex which was initialized as zero. 
6.	Nested For loop and logical operators have been used to loop through rows to get the total volume, starting price and the ending price.
7.	To get the total volume we have used the If Then statement. If the ticker is at the correct cell then the total volume will be calculated by adding the present value to the previous value.
8.	To calculate the starting price, we have used the logical operators to find out whether the current row is the first row for the respective ticker or not. If it the first row of the said ticker then the starting price value is equal to that of the respective cell. 
9.	To calculate the ending price, we have used the logical operators to find out whether the current row is the last row for the respective ticker or not. If it the last row of the said ticker then the ending price value is equal to that of the respective cell. 
10.	After the loop ends for each ticker, the output data was stored in the “All Stocks Analysis” worksheet.
11.	From the stock’s analysis of the year 2018, it is found that except “ENPH” and “RUN” all other stocks are not performing well.
12.	From the stock’s analysis of the year 2017, it is found that except “TERP” all other stocks are performing well. The stocks of “DQ”, “ENPH”, “FSLR” and “SEDG” are even having return more than 100 percentage.
13.	By using this code, we can find the total volume and the yearly return for any given year if we have the necessary data.
