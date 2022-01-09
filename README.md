# Stocks-Analysis

## Overview of Project
The performance of stocks from 2017 and 2018 was evaluated using visual basic for applications (VBA). The VBA code was refactored to loop through a dataset of the entire stock market over two years to determine the annual return on investment (ROI). 

## Results
As seen below, the stocks evaluated had a better performance overall in 2017 than in 2018. In 2017 all of the stocks had a positive ROI, except for TERP, which ended with a return of -7.2%. In 2018 the only stocks with a positive ROI were ENPH and RUN. The stock with the largest change in ROI between the two years was DQ, with a return of 199.4% in 2017 and a return of -62.6% in 2018.

![All Stocks Analysis 2017](https://user-images.githubusercontent.com/60076980/148702944-49a44d9d-a0d0-4c82-81bf-7f5c8c69a246.png)
![All Stocks Analysis 2018](https://user-images.githubusercontent.com/60076980/148702945-c80da944-c80f-4f16-9549-eecfd0169852.png)

A message box was added to show the elapsed run time for the script. The original code took .996 seconds to run the 2017 data and .984 seconds to run the 2018 data. After refactoring the code, the 2017 data was run in .230 seconds and the 2018 data was run in .184 seconds. This shows that refactoring the code significantly improved the run time of the script. 

### Original Timings
![VBA_Challenge_2017_OriginalTimings](https://user-images.githubusercontent.com/60076980/148692183-70d37f74-c929-4e50-8131-eb157161a702.png)
![VBA_Challenge_2018_OriginalTimings](https://user-images.githubusercontent.com/60076980/148692186-74355694-a22d-4731-a627-a9a76122c15e.png)

### Refactored Code Timings
![VBA_Challenge_2017](https://user-images.githubusercontent.com/60076980/148692011-46427bc1-7417-46b7-8463-b0070f37afd1.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/60076980/148692015-f4940447-ed90-4392-8f2a-f60803709a5d.png)

## Summary
There are several advantages to refactoring code. Refactoring ultimately leads to better code by making it fresher and easier to maintain and read. The disadvantages of refactoring code are that it is a time consuming process and a great deal of debugging may be necessary. 

As evidenced in the timing images above, refactoring code also leads to faster execution times. The primary disadvantage that I encountered while refactoring the original code was the amount of time spent debugging. However, the majority of bugs were syntax errors on my part, so when written cleanly there are very few disadvantages to refactoring code.   
