# Module 2 | Assignment - Wall Street

## Overview of Project

### Purpose
    The purpose of this analysis is to summarize stock performance data in order to better visualize how each stock ticker performs on an annual basis.

## Results
    Stock performance was much better in 2017 than in 2018. In 2017, 11 out of 12 indices had positive returns and only one index had a negative return. In 2018, 10 out of 12 indices had negative returns and only 2 indices has positive returns.
    For 2017, the refactored VBA script took 0.8359375 seconds to complete, whereas the original script took only 0.078125 seconds to complete.
    ![Stock Performance for 2017](/resources/VBA_Challenge_2017.png)
    For 2017, the refactored VBA script took 0.828125 seconds to complete, whereas the original script took only 0.08984375 seconds to complete.
    ![Stock Performance for 2018](/resources/VBA_Challenge_2018.png)

## Summary
    An advantage of refactoring code would be to accomodate new functionality within the code. The original structure of the script may not be able to or be as efficient with satisfying the new functionality requirements, and would thus call for a refactoring. A disadvantage with refactoring code is that the developer updating the code may not be immediately aware of specific reasons code was written a certain way by the original developer, especially if the original developer is not sufficiently descriptive in their comments. In our case, refactoring the code actually worsened its performance. The refactored code actually took around 10 times longer to execute than the original code. It would not make sense to refactor the code in our case, since it results in terribly inefficient processing.