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



![alt text](http://url/to/img.png)
![alt text](http://url/to/img.png)
