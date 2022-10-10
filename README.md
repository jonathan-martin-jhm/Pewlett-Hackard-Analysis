# Pewlett-Hackard-Analysis

## Background
Now that Bobby has proven his SQL chops, his manager has given both of you two more assignments: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, you’ll write a report that summarizes your analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

### Overview of the Analysis:
The purpose of the analysis is to help the manager of Pewlett Hackard prepare for and mitigate effects of a large number of employees retiring.

1) Determine the Number of Retiring Employees by Title
2) Determine the Employees Eligible for the Mentorship Program

## Results
- In the retirement_titles.csv, a total of 133,776 employees were intially identified to be at retirement age from a list of 300,024 employees. Retirement age was defined as employees born between 1952 and 1955. The data set contains duplicates of employees that need to be removed, which are a result of employees changing titles during their tenure with the company. The total also contains former and current employees. The former employees need to be removed as well.

- In the unique_titles.csv, former employees and duplicates of employees were removed from the data set to yield a total of 72,458 employees at retirement age.

- The retiring_titles.csv file was created to retrieve the total counts of current employees at retirement age by position title. The query yieled a total of seven employee titles at retirement age. The largest sums of employees with retirement eligibility were shown to be at senior level positions, which comprised approximately two thirds of the retirement eligible employees. 

(retiring_tiles.png)

-The mentorship_eligibility.csv was created to provide a list of employees that are eligible to participate in a mentorship program. The eligible employees were selected by the birth year 1965, which totaled 1,549 current employees with eligibility.

## Summary

A total of 72,458 employees will need to be replaced when the "silver tsunami" begins to make an impact. The total employees eligible for the mentorship program totaled 1,549, which only covers 2.1% of the employees retiring. As such, I recommend expanding the mentorship program to provide more comprehensive plan to replace the senior positions vacated by retiring employees. A new query could me made to idenitify more employees to target for the mentorship program. A initial query that expands the birth year parameter from 1965 to 1965-1970 would broaden the list of eligible employees for the mentorship program. Additionally, the mentors would likely need to provide mentorship to multiple employees to cover the larger number of employees retiring.


