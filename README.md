# Pewlett-Hackard-Analysis

## Project Overview
Pewlett-Hackard has requested data to be collected and organized to determine role and training impacts of the "silver tsumami". That is employees who will be reaching retirement age in the comming 3 years. 

## Resources
- Data Source: departments.csv, dept_managers.csv, employees.csv, dept_emp.csv, salaries.csv, titles.csv
- Software: pgAdmin 4 version 6.7 

## Analysis Results
The analysis of the Pewlett-Hacker employee data show that:

Deliverable 1: The Number of Retiring Employees by Title
- There will be 72,458 total employees retiring
- 25,916	Senior Engineer
- 24,926	Senior Staff
- 9,285	Engineer
- 7,636	Staff
- 3,603	Technique Leader
- 1,090	Assistant Engineer
- 2	    Manager
This can be seen in Figure 1:
### Figure 1: Retiring Tiles
![Original](https://github.com/Jarney903/Pewlett-Hackard-Analysis/blob/main/retiring_titles.png)
<br />

Deliverable 2: The Employees Eligible for the Mentorship Program
- There are 1,549 Employees Eligible for the Mentorship Program
- 55 Assistant Engineers
- 383 Engineers
- 310 Senior Engineers
- 406 Senior Staff
- 318 Staff
- 77  Technique Leader
- 0   Managers
This can be seen in Figure 2:
### Figure 2: Mentorship_Eligibility
![Original](https://github.com/Jarney903/Pewlett-Hackard-Analysis/blob/main/mentorship_eligibilty.png)
<br />

## Analysis Summary
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
- There will be 72,458 total employees retiring
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
- Assuming each mentor can mentor 25 employees, there are not enough Managers, Technique Leaders, Senior Staff, or Senior Engineers to mentor. 
- This question is shown in the following analysis tables.
This can be seen in Figure 3:
### Figure 3: Mentorship_Eligibility vs Retired Positions
![Original](https://github.com/Jarney903/Pewlett-Hackard-Analysis/blob/main/mentorship_eligibilty_vs_retired_positions.png)
<br />
- Furthermore there are zero managers to act as mentors, as shown in counting eligible mentors by title in figure 4 below.

### Figure 4: Mentorship_MGMT
![Original](https://github.com/Jarney903/Pewlett-Hackard-Analysis/blob/main/mentorship_MGMT.png)
<br />