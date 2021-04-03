# Pewlett-Hackard-Analysis
## Overview of the Analysis
Pewlett Hackard is making preparations for the baby boomers that will be retiring in the near future. The first preparation PH is making is to provide a retirement package for those who meet a certain criteria. The second preparation is to anticipate the positions that will need to be filled. The analysis performed focuses on the following two parts: determining the number of retiring employees per title, and identifying employees who are eligible to participate in a mentorship program. 

## Results
In the deliverable 1 analysis, I have created a retirement title table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955. The following image below shows an excerpt of 10 employees from the table that contains the emp_no, first_name, last_name and title. 

![unique_titles.PNG](https://github.com/WTAN241/Pewlett-Hackard-Analysis/blob/main/Images/unique_titles.PNG)

Then, using the table above as a basis, I have removed the repetitive values and have created a table summarizing the different titles and number count of the current employees who were born between January 1, 1952 and December 31, 1955. This table provides the following insights:

![retiring_titles.PNG](https://github.com/WTAN241/Pewlett-Hackard-Analysis/blob/main/Images/retiring_titles.PNG)

1. 33% of the current employees who will be retiring are senior engineers
2. A large proportion of current employees who will be retiring hold senior level or managerial level positions
3. Only two current employees who hold manager positions will be retiring
4. 50% of the current employees who will be retiring work as engineers

The following image shows an excerpt of 10 employees from a table that shows the data of current employees who are eligible for the mentorship program. These employees were born between January 1, 1965 and December 31, 1965 and would be good candidates to participate in the mentorship program. This table provides the following insights:

![mentorship_eligibility.PNG](https://github.com/WTAN241/Pewlett-Hackard-Analysis/blob/main/Images/mentorship_eligibility.PNG)

1. There is a total of 1549 current employees who are eligible to participate in the mentorship program
2. The highest proportion (28%) of employees eligible for this program hold the title of staff
3. The second largest proportion (27%) of employees eligible for this program hold the title of senior engineers
4. The average duration of these employees at the firm has been 28 years

## Summary

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Approximately 72,458 roles will have to be filled as the "silver tsunami" begins to make an impact. To address this question, I have refined the previous table of retirement titles to only show the current employees and exclude the employees that are no longer in the firm. The folllowing query was made to only include the current employees who are expected to retire in the near future.

![roles_to_be_filled.PNG](https://github.com/WTAN241/Pewlett-Hackard-Analysis/blob/main/Images/roles_to_be_filled.PNG)

The following image shows the output of 25 employees who are expected to retire soon. 

![current_retiring_employees.PNG](https://github.com/WTAN241/Pewlett-Hackard-Analysis/blob/main/Images/current_retiring_employees.PNG)

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

There are more than enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees. By using the query below, I was able to count the number of employees per title that are eligible for the mentorship program.

![mentorship_eligibility_by_title.PNG](https://github.com/WTAN241/Pewlett-Hackard-Analysis/blob/main/Images/mentorship_eligibility_by_title.PNG)

The table below shows the number of employees per title that are eligible for the mentorship program.

![mentorship_eligible_titles.PNG](https://github.com/WTAN241/Pewlett-Hackard-Analysis/blob/main/Images/mentoring_eligible_titles.PNG)

According to the table below which shows the number of current employees that are retiring per title, there are more than enough qualified and retirement-ready employees to mentor the next generation of Pewlett Hackard employees. 

![current_employees_retiring_titles.PNG](https://github.com/WTAN241/Pewlett-Hackard-Analysis/blob/main/Images/current_employees_retiring_titles.PNG)