# Pewlett-Hackard-Analysis
This analysis aimed at identifying the number of employees per title from each department who are retiring. Additionally, this analysis helped to  identify employees who are eligible to participate in a mentorship program.
## Deliverable 1 
By using the ERD that I created earlier in the beginning of the module, I created a Retirement Titles table that held all the titles of employees who were born between January 1, 1952 and December 31, 1955.Then I used the DISTINCT ON statement to create a table that contained the most recent title of each employee. After that, I used the COUNT() function to create a table that had the number of retirement-age employees by most recent job title. The instructions to complete the section were:
(1) Retrieve the emp_no, first_name, and last_name columns from the Employees table,
(2) Retrieve the title, from_date, and to_date columns from the Titles table,
(3) Create a new table using the INTO clause,
(4) Join both tables on the primary key,
(5) Filter the data on the birth_date column then order by the employee number,
(6) Export the Retirement Titles table from the previous step as retirement_titles.csv,
(7) Copy the query from the Employee_Challenge_starter_code.sql and add it to your Employee_Database_challenge.sql file,
(8) Retrieve the employee number, first and last name, and title columns from the Retirement Titles table,
and (9) Use the DISTINCT ON statement to retrieve the first occurrence of the employee number for each set of rows defined by the ON () clause.






