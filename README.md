# Refactoring VBA Code and Measure Performance

## Overview of Project

Steve originally wanted to be able to pull the stock for the company DAQO (Ticker: DQ) to determine its viability for investment.  Initial analysis indicated that the first year (2017) the stock skyrocketed by nearly 200%, but that in 2018 it dropped by over 63%.  Based on this, Steve decided he wanted to analyze a larger number of stocks.
  

### Purpose

This project was to take the code and apply it so Steve could analyze larger datasets.  Based on the code developed for DQ and then for the rest of the stocks in the current dataset, refactoring of the code was necessary to ensure it ran in a timely manner for larger amounts of data.

## Results
### Comparison of stocks
Based on the data, 2017 was actually a very good year.  All but one of the stocks' values went up and half went up by 50% or better.  And of those that had a significant increase in the value of their stock, DQ lead, with an increase of nearly 200% by year end.  However, 2018 was was not kind.  All but 2 of the stocks dropped and nearly half of them dropped by 20% or more.  On the upside, the 2 stocks that did well, had an increase of over 80% each.

### Comparison of execution time of scripts
Initially, the code for all stocks based on the year selected ran a bit long.  For 2017, the execution time was .93 seconds and for 2018, it was .95 seconds.  Since Steve would like to be able to do analysis on larger data sets of stocks, refactoring of the code was necessary to try to reduce the execution time.  After refactoring, the execution time for 2017 and 2018 was .77 seconds. 

## Summary

-Advantages of Refactoring
>Refactoring is beneficial when you have some code that works, but perhaps it is not elegant or streamlined enough to accommodate larger data sets.  
>Additionally, refactoring is a way to make the code more readable and more easily translated by others.  Fresh eyes on code is also a great advantage when refactoring other's code.

-Disadvantages of Refactoring
>Refactoring can become very messy and cumbersome.  It can be difficult to read others code, especially if there are no notes.
>Refactoring can potentially cause the opposite of what you are trying to achieve; longer running code, etc.
