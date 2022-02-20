# Pewlett-Hackard-Analysis

## Overview of the Analysis

The purpose of this analysis is to prepare Pewlett-Hackard, a company with several thousand employees, for the upcoming “silver tsunami”. Many employees will begin retiring at a rapidly in the next few years and so the company wants to be prepared with the retirement packages, openings as a result of these retirements and new and incoming employees’ training. 


## Results

1. The list of retiring employees was produced first to see how many of the employees are set to exit Pewlett-Hackard. This first code produced a list which had duplicates that showed multiple positions held by the same employee as separate entries. 

![Pic]( https://github.com/msha789/Pewlett-Hackard-Analysis/blob/7f93813ba33832207e99c749fce9ccbcab5547f8/Screen%20Shot%202022-02-20%20at%202.06.15%20PM.png)

2.	The above list was modified to remove the duplicates to retrieve a list of all employees se to retire with only entries of their latest positions within the company. 

![Pic]( https://github.com/msha789/Pewlett-Hackard-Analysis/blob/7f93813ba33832207e99c749fce9ccbcab5547f8/Screen%20Shot%202022-02-20%20at%202.02.44%20PM.png)

3.	This next table shows the tallies of all employees grouped by their job titles set to retire within the next couple years. This shows the number for exiting positions for each level of employment within Pewlett-Hackard.

![Pic]( https://github.com/msha789/Pewlett-Hackard-Analysis/blob/7f93813ba33832207e99c749fce9ccbcab5547f8/Screen%20Shot%202022-02-20%20at%202.03.03%20PM.png) 

4.	The last table, below, shows the employees in Pewlett-Hackard eligible for the mentorship program. This was a merge of three tables and filtered to remove duplicates to only show employee’s current or most recent positions. 

![Pic]( https://github.com/msha789/Pewlett-Hackard-Analysis/blob/7f93813ba33832207e99c749fce9ccbcab5547f8/Screen%20Shot%202022-02-20%20at%202.03.19%20PM.png) 


## Summary

_How many roles will need to be filled as the "silver tsunami" begins to make an impact?_

The table below contains all the information about the employees that are about to retire.  To get the number of positions that will open up in next couple years I ran additional query that breaks down how many staff per positions will retire per department. 

![Pic]( https://github.com/msha789/Pewlett-Hackard-Analysis/blob/7f93813ba33832207e99c749fce9ccbcab5547f8/Screen%20Shot%202022-02-20%20at%202.03.48%20PM.png) 

_Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?_

Assuming that higher positions are the only employees qualified for mentoring, the query was additionally filtered to only search for these higher positions: Senior Engineer, Senior Staff, Technique Leader, and Manager. 

![Pic]( https://github.com/msha789/Pewlett-Hackard-Analysis/blob/7f93813ba33832207e99c749fce9ccbcab5547f8/Screen%20Shot%202022-02-20%20at%202.04.35%20PM.png) 


