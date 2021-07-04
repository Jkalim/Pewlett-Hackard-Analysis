# Pewlett-Hackard-Analysis

## Project Overview
The purpose of the analysis is to prepare the manager for the "silver tsunami" which mostly 
regard the upcoming retirement of current employees. Knowing the number of employees that will be
retiring from each department will help the manager figure out how many people will need to be replaced
and determine how many people may need to be promoted and how many need to be hired.

## Resources
-Data Source:departements.csv, dept-emp.csv, dept_manager.csv, employees.csv,salaries.csv, titles.csv
-Sofware: PostgresSQL

## Resuslts
 -The analysis shows a totalof 90,398 current employees will retire from the company from each department as follow:
  - Senior Engineer: 29,414
  - Senior Staff: 28,254
  - Engineer: 14,222
  - Staff: 12,243
  - Technique Leader: 4,502
  - Assistant Engineer: 1,761
  - Manager: 2
 
 -Due to the upcoming retirees, a group of 1,549 current employees will start a mentorship program
to help facilitate the transition of the new staff to be hired to replace the retirees. 

 -The engineering department will be mostly affected as a large number senior engineers
and engieers will be retiring.

 -The company will need a new to hire about 14,222 stafff members as their senior staff will be 
gone as well. 
  
## Summary
A grand total of 90,398 roles will need to be filled as a results of the upcoming retirees. Only 1,549
current employees are qualified for the mentorship group. The ratio of retirees to qualified mentors 
is about 58 to 1. It does not seem to be enough to mentor the new staff coming in as the gap between
qualified retirees and qualified mentors is too high. A query that provides the count of current
employees qualified eligilible for membership per title is useful as it gives an idea of how many 
new hires each mentor will be responsible for. A table showing the ritirement eligibility date of 
the mentors will be useful as well as it will help monitor and better prepare for the next wave of
"silver tsunami."
