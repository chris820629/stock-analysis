# stock-analysis
## Overview of Project 
### Purpose of the analysis 
- Create a stock performance dashboard with the interested stock tickers, total of 12 tickers
- The dashboard consists of the year analysis was executed, ticker symbols, total trading volumes of each ticker, entire year of return of each ticker 
- Established VBA/Macro coding for ease of analysis. User can easily pick the year he or she would like to perform the analysis on and receive instant result on the "All Stocks Analysis" tab
### Results 
1. Stock performance 2017 vs 2018
  - Overall, the stocks in 2018 perform worse than previoous year, 2017 
  - TERP is the only stock with consecutive negative return for both 2017 and 2018
  - DQ shows the highest fluctuation where it has almost 200% return in 2017 but has the highest losss in 2018 falling by 62.6% 
2. Execution time original vs. refactored 
  - The refactored execution time is shorter than the original script

### Summary
***Refactoring code (Concept):
1. Advantage
  - Reduce duplications in the code: improve run time as well
  - Easier to read/less complex: easier for others to understand your code
2. Disadvantage
  - Losing context: it is hard to understand and trace back to the original coding pattern structure by the first coder
  - Imprecise refactoring can easily cause bugs: it is harder to breakdown the functions to debug line by line. 
***Refactoring code (VBA): 
1. Advantage of refactoring
  - Looks cleaner with the comments in green to also better help breaking down the code pattern, also explaining why each line of code is for
  - Reduces the nested for loop which can be messy when you are looping through two kinda of array. 
2. Disadvantage of refactoring
  - The comments make the codes a bit hard to follow especially if you have "If" and "For" functions embeddeed. In this case, the for loop takes up the entire window and I have to screw back and forth to review the for loop code.
