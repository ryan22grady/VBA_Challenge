# VBA_Challenge
Refactoring of 2017 and 2018 Stock Analysis
## Overview of Project
The purpose of this project was to refactor a VBA code to collect stock information for 2017 and 2018 to help Steve determine whether stocks are worth investing. While code was created to help Steve previously, the goal now is to decrease the time needed to run the script while incorporating more data. 
### Results
The refactoring began first by incorporating the code needed to create the input box, chart headers, ticker array, etc. Then, using the prescibed steps to reevaluate the previous coding, I began to integrate previous coding lessons such as "for" loops, "if-then" statements, and  prescription of data types. Each step was listed in the comments section of the code as well. 
#### Refactored Code

<img width="788" alt="Refactored Code" src="https://user-images.githubusercontent.com/84995704/123489946-b8804b80-d5d8-11eb-9191-74461e3bc78c.png">

The new code allowed for the assignment of tickerVolumes, tickerStartingPrices, and tickerEndingPrices to each symbol. By doing this method and avoiding the nested "for" loops, the analysis could be completed much faster. See the new run times below.
#### Run-times for each Stock Year

<img width="316" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/84995704/123490225-48be9080-d5d9-11eb-8660-b1afc37a2336.png">
<img width="281" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/84995704/123490243-4d834480-d5d9-11eb-8f73-b2fc650829cc.png">

### Summary
#### Refactoring Code
The obvious advantage of refafactoring is the opportunity to relook previous code and make it more efficient by taking fewer steps, using less memory, and improving the logic of the code. The disadvantage of refactoring is that it might not translate to the everyday coder; creative steps (if not documented in detail) can become useless if the lowest common denominator of coders can not understand the logic and intent. 
#### Refactoring VBA Script
A benefit of refactoring in VBA script that it is relatively easy acquire the previous coding and determine ways to incorporate creative shortcuts for efficiency, especially if you have a mastery of the syntax of the VBA. Likewise, a disadvantage would be a lack of mastery of the sytax makes it very difficult to understand the logic and intent of the previous coder, particularly because it is not easily intuitive. 
