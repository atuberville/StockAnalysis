# VBA of Wall Street

## Purpose

The initial analysis was to see if the DAQO stocks were a good 'green' investment. We soon found that in 2018, they had a negative rate of return. Afterwards, we expanded this analysis to see how all the stocks on the list were doing and which ones were better investments based on historical 2017 and 2018 data. 
## Results
Most of the stocks in 2018 decreased from their 2017 returns, with the exception of ENPH and RUN which both saw a positive return in 2018. The ENPH stock still saw a significant decrease from 129% to 81% whereas the RUN stock saw an increase from 5.5% in 2017 to 83% in 2018. I would think that there were some environmental or industry specific factors that caused such a large increase and this would need to be researched prior to investing in RUN. 
The initial execution times for the first code was >3 seconds, after refactoring, the code returned in slightly over one second for each year.
## Summary
One of the advantages of refactoring code is the decreased run time and this would be extremely important if the data were going to increase or be used consistently for analysis. Another advantage is being able to find the answer and test the code prior to improving the macro. A major disadvantage is the amount of time and additional research it takes to refactor a code all at once. The person writing the code will learn to improve as time goes on and will hopefully, find ways to repurpose an extremely successful code that works quickly.
In this specific situation, refactoring saved over a second, which doesn't seem like a lot however, once more data is added the refactored code will be a huge benefit. In the first code we wrote the data looped through each process for daily volume and return. In the second one we combined these steps instead of doing them in a hierarchical order. Additionally, the second code was better drafted, and the readability was improved with clearer comments and the addition of white space. The first code test is attached to the respository as a .txt file labled 'InitialCode'. The working code that returned the same data more efficiently is attached in a .txt file labled 'Workingcode'. 
