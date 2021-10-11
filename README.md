# pewlett-hackard-analysis

## Overview
The purpose of this analysis is to help Bobby determine the number of retirees per title at Pewlett Hackard, as well as to identify which employees would be eligible for a new mentorship program for this company. This program would allow near retiree age individuals to train their successors before they retire.

## Results
Tables were created to perform these analysis. First, we consolidated all of retiree age employees (employees born between 1952 and 1955) into a table along with the titles they've had at the company and the dates during which they held those titles. This table can be seen in the attached csv document titled "retirement_titles. Second, we narrowed down this list to remove duplicates for people that have held multiple titles at PH. In this table we only kept the employee numbers, their first and last names, and their current title. We weren't interested in previous titles held, so we removed those. This information can be found in the attached csv titled "unique_titles". Lastly, during this first part of the analysis we decided to do a count of exactly how many employees with each unique title are nearing retirement age. In order to determine whether a mentorship program could work to train future employees to take over for those that are retiring we created another table that contains a list of all of the employees that could be eligible for this membership program (employees born in 1965. 

### Major points gathered from these 4 tables
- First, we can see that there are a total of 90,398 employees of retirement age. This seems like an extremely large number. 
- Additionally, the positions that will be most impacted will be Senior Engineers, Senior Staff, Enigineers, and Staff. These four positions make up about 93% of the retiree age individuals.
- There aren't very many retirement age employees in higher up roles at Pewlett Hackard.
- Only 1,549 employees were identified to participate in the mentorship program.

## Summary
- As the "silver tsunami" begins to make an impact there will need to be a total of 90,398 roles filled.
- However, there were only 1,549 employees identified to be in the mentorship program. This is a mere 1.7% of the total retirement age employees. This is no where near anough to lessen the impact of the silver tsunami.
- Only employees born between a one year period were identified to be eligible for this program, which seems doomed to fail. A much larger range should be considered for this program in order to avoid this disaster and a new table created with these additional employees to better analyze the impact this would have. Especially since most of the roles being abandoned are already roles occupied by many of the folks in the mentorship program.
- It would be important to gather information as to how many of the retirement age employees actually do plan to retire and if any of them have a plan in place for a successor if they do so.
