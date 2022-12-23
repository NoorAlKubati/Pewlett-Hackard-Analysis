# Pewlett-Hackard-Analysis
This analysis aimed at identifying the number of employees per title from each department who are retiring. Additionally, this analysis helped to  identify employees who are eligible to participate in a mentorship program.

## Results
By using the ERD that I created earlier in the beginning of the module, I created the Retirement Titles table that held all the titles of employees who were born between January 1, 1952 and December 31, 1955.Then I used the DISTINCT ON statement to create a table that contained the most recent title of each employee. 


![Picture here](https://github.com/NoorAlKubati/Pewlett-Hackard-Analysis/blob/main/Deliverable%201.png)


After that, I used the COUNT() function to create a table that had the number of retirement-age employees by most recent job title. The result of that analysis were grouped by title and showed that there were only seven titles for the retiring employees. As shown in the picture, most of the openings will be in the senior engineer and senior staff, and the lowest one in the manager title.

In the second analysis, results showed that there were 1549 employees who were eligible for the mentorship program. All of these employees were born in 1965 and are still current employees of the company.

## Summary

This analysis gives a quick overview of how many openings will take place and what titles need to be filled after these employees retire. The table summarizes the numebrs in brief. Additionally, employees who meet the criteria to the mentorship program were listed in the mentorship_eligible table for future access or extra filtering. 












