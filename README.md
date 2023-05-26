# Python-homework: PyBank Data Analysis

In this task our attempt will be to analyze the financial records of PyBank and generate a summary report.

## Table of Contents
* [Code & Resource file](#code)
* [Python Variables](#python-variables)
* [User Defined Functions](#user-defined-functions)
* [Report Summary](#report-Summary)

## Code & Resource file

Code file available [_here_](https://github.com/UpadhyayShweta/Python-homework/blob/ba98034d3b2562b47c638426f1df79b9a3a9a103/PyBank/main.ipynb).

Resource file is available [_here_](https://github.com/UpadhyayShweta/Python-homework/blob/50e59d660c8160af576c04f61ddf02f01a7bf498/PyBank/budget_data.csv)

## Python Variables

For this analysis we have primarily used local variables and explored Python dictionary and dictionary inside list objects.

## User Defined Functions

We have used using python script to creat UDFs in order to calculate financial KPIs and generate our custom report.
Functions created and their explaination:
```python
1. total_months() #to calculate the total number of months in our file and remove and duplicate record present for same month.

2. count_total() #calculates the net total amount of Profit/Losses occured and average change happened over entire period.

3. greatest_profit_or_loss() # calculates the greatest increase in profits and greateset decrease in losses(date and amount) over the entire period.

4. financial_analysis_report() #generate our financial analysis report in the required format
```

## Report Summary

Resulting financial report post our data analysis: 
```python
Financial Analysis 
------------------------------
Total Months: 86
Total: $38382578
Average  Change: $-2315.12
Greatest Increase in Profits: Feb-2012 ($1926159)
Greatest Decrease in Profits: Sep-2013 ($-2196167)
```
