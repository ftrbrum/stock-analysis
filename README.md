# stock-analysis

Analysis of Green Energy Stocks

## Overview of Project

### The purpose of this project was to refactor the initial VBA code on green_stocks.xlsm file to make it more efficeient.  This should also allow the file to be edited and debugged easier in the future.

## Analysis and Challenges

### Analysis of VBA in green_stocks.xlsm

![green_stocks_2017.png](resources/green_stocks_2017.png)
![green_stocks_2018.png](resources/green_stocks_2018.png)

As shown in the images above, the first version of the VBA code ran in over 0.9 seconds.

### Analysis of VBA in VBA_Challenge.xlsm

![VBA_Challenge_2017.png](resources/VBA_Challenge_2017.png)
![VBA_Challenge_2018.png](resources/VBA_Challenge_2018.png)

As shown in the images above, the refactored version of the VBA code ran in under 0.16 seconds. This is an improvement of 0.74 seconds over the previous VBA code.

### Advantages and Disadvantages

The advantages for refactoring the VBA code for All Stocks Analysis worksheet were many.  The previous code was written between 6 different macros.  Once the VBA code was refactored the only macros needed for the updated file were AllStocksAnalysisRefactored, DQAnalysis, and yearClearWorksheet.  The code is now easier to read and maintain for any future revisions needed.

The disadvantges for refractoring VBA code is the time it can consume for other projects.  It might be more time efficient to rewrite the code from scratch. 

## Conclusion

With the refractered code, we have increased performance by an average of 0.74 seconds and created a more readable code for any future updates.
