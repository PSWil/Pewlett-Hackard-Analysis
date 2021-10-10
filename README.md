# Pewlett-Hackard-Analysis
## Overview
In this project we were asked to analyze the workforce at Pewlett Hackard to determine which employees will be eligible for retirement in the near future, and if those retiring employees would be a nice fit for a mentoring program that Pewlett Hackard would like to impliment in order to make this coming transition easier.  To accomplish this, I have been tasked with identifying employees who are most likely to retire soon by their title and employees who could transition to a part time mentorship program as opposed to retiring outright. To manage the employment records and data and identify likely candidates I used PostgresSQL. A visuallization of the dataframe structure is shown below.

![Employee DB](https://github.com/PSWil/Pewlett-Hackard-Analysis/blob/main/EmployeeDB.png)

## Results
### Retiring Pwelett Hackard Employees
To determine which employees are eligible for retirement we were asked to sort them by a few different parameters, primarly by the year they were born, focusing on those born between the years of 1952 and 1955. Looking at the list of employees that may be retiring soon we can gather a few quick data points:
1. There are over 90,000 employees that may potentially be retiring soon.
2. Almost 60,000 of those are senior level employees.
3. 43,636 employees are engineers
4. 40,497 employees are staff
5. Only 2 managers need to be replaced

![Retiries by Deptarment](https://github.com/PSWil/Pewlett-Hackard-Analysis/blob/main/Data/retirees_by_dept.csv)

### Eligibilty for Mentorship Program
Eligibility for the mentoryship program is determined by a select few factors to those employees; who have current roles in the company born in 1965 and have no current termination date. 
1. Overall there are 1,550 employees eligible for the mentorship program.
2. Of those, 741 employees are senior level employees.
3. 748 employees are engineers.
4. And 724 employees are staff members.
5. Under the current criteria there are no managers who qualify for the mentorship program. 

## Summary
Under its current criteria for eligibility the mentorship program is not currently sustanible. With over 90,000 positions that will potentially need to be filled and there being only 1,550 employees currently eligible to join the mentorship program as mentors, it will be impossible for the mentors to divide their time between all the employees that could be under the mentorship and provide the quality of knowlege that the company would like to pass on and perserve. 

Expanding the mentorship program to include those employees born between 1952 and 1955 will expand our pool of mentors and enable Pewlette Hackard to retain the necessary knowlege to propel the company forward and to engage in new venturs while having an exceptional understanding of the business processes that led to previous growth.

