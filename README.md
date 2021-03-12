# Stock-Analysis
##1) Overview of the Project
Steve's parents want to invest in green energy, and they want to invest in DAQO stock. Steve will help them do the investment, but he will analyze some other stocks to take a better decision, and he collected the data on these stocks in an excel file.

##2) Results
All the stocks have ended with a end of year price bigger than a start of year price in 2017 except for "TERP" ticker which lost some value at the end of 2017.
However, in 2018, most of the stocks have lost value and ended up in the red zone except for "ENPH" and "RUN" tikers.
The DQ stock has gained value in 2017 but lost some value in 2018, so it is not the best choice for Steve's parents. the "ENPH" has gained value in both years and would be a better choice than "DQ", and RUN ticker comes in second place.

The code execution times have been significantly reduced significanly when the code is refactored.For the year 2017, the timing has been reduced from 0.864 (link: https://github.com/mdabbous88/Stock-Analysis/blob/main/Execution%20time%20of%202017_original%20code.png) seconds to 0.230 (resources.zip folder)
for the year 2018, the timing has been reduced from 0.998 seconds (link: https://github.com/mdabbous88/Stock-Analysis/blob/main/Execution%20time%20of%202018_original%20code.png) to 0.229 seconds (Resources.zip folder).

##3)Summary
1.a.The advantages of refactoring a code can be summarized as below
-Faster code exection
-Less memory space used
-Less RAM required to execute the code
-less probability of failure to execute the code.

1.b.The disadvantages can be summarized as below
-More code complexity and the use of advanced functions such as Arrays which could not be simple task to do.

2. The pros apply to the code refactoring we did because it shows faster execution times, less memory usage because we are using arrays (1 array for starting price,1 array for ending price) in place of other multiple variables (11 starting price, 11 ending price). If the code gets bigger, and we intend to analyse more stocks, the code could potentially fail to execute.

The cons apply when using arrays and accessing them instead of having single variable. This has added some comlexity to the code.


