# Green Stock Analysis

## Overview of Project

### Purpose
The initail purpose of this analysis is to review the returns of multiple stocks quickly. By refactoring the origianl code we created we should be able to speed up the time the code takes to run. We are useing a relatively small sample size of twelve companies we are reviewing and limiting the data to just the years of 2017 and 2018. Refactoring our code will allow for quicker computation if we were to add larger data sets.

## Results
![Pre_refactor_2017](https://user-images.githubusercontent.com/80363261/112741191-01c4ee80-8f49-11eb-8e3e-b129890821cd.png)
![Pre-refactor_2018](https://user-images.githubusercontent.com/80363261/112741192-038eb200-8f49-11eb-808e-15cf4ee3556e.png)

The above pictures are a capture of the time it took our original code to run. Not too bad but we can make it run faster by pulling all data we need with the first loop over the data set. By refactoring the code we are able to decrease the output time as seen in the pictures below.

![VBA_Challenge_2017](https://user-images.githubusercontent.com/80363261/112741197-0ab5c000-8f49-11eb-9ea9-e7575400e6ff.png)
![VBA_Challeng_2018](https://user-images.githubusercontent.com/80363261/112741198-0c7f8380-8f49-11eb-8127-29b30c287c4f.png)

## Summary
The advanatages of refactoring code is that the output is processed faster and the code is a little cleaner and more streamlined by pulling all information in the first pass of the data. Allowing for larger data sets with many more companies being reviewed. A disadvantage of refactoring would be whether or not it is a beneficial investment of time and resources. By refactoring our script we have added a quick faster feedback for Steve and allowed for adding more companies to analysize for his family. One disadvantage to the refactored code we have is we will still need to add any new companies to the "tickers" dimension we have established, as it is set to only loop through the twelve companies we set in the "tickers" array.
