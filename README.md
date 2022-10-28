# Pewlett-Hackard-Analysis
## Overview of the analysis:
#### The purpose of this analysis was to be able to take several differrent data sets and tables and bring them togehter to find the connections between all of the different data sets. By doing this we were able to find out the number of employees who were able to retire and other important info. This information was able to help the company plan their futures and find out what steps are needed to help prepare for the large amounts of retirees.
## Results:
####   * By looking at the mentorship_eligibility table we were able inspect look at the emp_no as well as find the employee names, birth dates, titles and much more.
####   * By looking at the retiring titles table we were able to look at the amount of employees for each title and see who could retire in each postion. For example, there are 2 managers set to retire.
####   * Additionally, there were a total of 9,285 engineers eligibile to retire.
####   * There were also 24,926 people retiring in the Senior Staff title.
![image](https://user-images.githubusercontent.com/112527054/198445886-47d1276c-e823-49a2-8d91-6e83e6f980db.png)
![image](https://user-images.githubusercontent.com/112527054/198454023-6a605e34-7bda-4db8-a572-3d5e85d43330.png)

## Summary:
### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
#### There will be a total of 72,458 roles to be filled so that there are no gaps in positions.
### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
#### There are not enough qualified employees ready to fill the positions that are soon to be available. If the company is able to get more employees eligible to participate in the mentorship prgram then they may be able hire more employees and train them for roles. This may include training current employees for promotions so that lower title jobs are available that may be easier to train. 
#### Query examples:
#### SELECT COUNT(emp_no)
#### FROM mentorship_elibility;
#### SELECT *
#### FROM retiring_titles;
