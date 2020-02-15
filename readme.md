#  Analysis of Kickstarter projects to uncover market trends

Background
Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.
Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. 
I organized and analyzed a database of 4,000 past Kickstarter projects in order to uncover any hidden trends.

Features used:
Conditional formatting, advanced formulas, pivots, charts et ct.

1) Used conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

2) Created a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.

3) Used conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale starts at 0 and with dark shade of red, transitioning to green at 100, and blue at 200.

4) Created a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.

5) Created two new columns, one called Category at Q and another called Sub-Category at R, which use formulas to split the Category and Sub-Category column into two parts.

6) Created a new sheet with a pivot table that analyzes my initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

7) Created a stacked column pivot chart that can be filtered by country based on the table I have created.

8) Used formulas to convert Uix timestamps into Excel data format

9) Visualized a pivot table with a chart

Prepared a summary to answeer the following questions:

Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
What are some limitations of this dataset?
What are some other possible tables and/or graphs that we could create?

Further analyzed the dataset to categorize projects by:

Goal
Number Successful,
Number Failed,
Number Canceled,
Total Projects,
Percentage Successful,
Percentage Failed,
Percentage Canceled.
