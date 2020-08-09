## Overview of Project: Explain the purpose of this analysis.

The purpose of the analysis was to create a macro that would be easily accessible for Steve, or any other end-user to utilize.  Specifically, we were looking at 12 different stocks that Steve's parents were thinking about investing in. We wanted to see the total volume of each stock (meaning how often each stock was traded) from the beginning to the end of the year for the years we have data on, which are 2017 and 2018.  Additonally we wanted to see the percentage return for each of the 12 stocks over a year long period.  By doing this analysis, Steve will be somewhat better able to recommend which of those stocks his parents should invest in, since apparently putting their money in an S&P 500 index fund or something isn't what they're looking for.

### Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.
2017 was a much better year for every single one of the 12 selected stocks except for the company with "RUN" as their ticker.  The oringinal stock that Steve's parents were interested for *big brain* reasons, "DQ" highlights the difference in performance from '17 to '18.  In 2017, "DQ" stock prices rose 199.4% but in 2018, the price fell 62.6%.  Overall, this seems like a very volatile sector, and for people that can be assumed to be close to retirement, I would suggest that they look at either index funds, vanguard 20XX funds, or frankly, just fixed income options.  

### Summary: In a summary statement, address the following questions.

### What are the advantages or disadvantages of refactoring code?
Refactoring code makes it cleaner and easier to read.  It's like editing a draft in order to make it more presentable.  You're not changing the behavior, or the outcome of the code, you're just making it run more efficiently.  A possible disadvantage is that you introduce bugs (which I certainly did) into the code by refactoring it.  Those bugs will have to be addressed before you can run the code against the original to see if it performs more efficiently.

### How do these pros and cons apply to refactoring the original VBA script?
The refactored code does look cleaner and has a better format that makes it easier to read line by line.  However, in the process of refactoring the code, I must've ran into dozens of bugs that I created by incorrectly writting it.  Given the time I had to put into writting it correctly, compared to the small difference in efficiency gained, I don't know that it was worth it in a vacuum to refactor in this scenario.  (Of course it was well worth it as a learning experience).
