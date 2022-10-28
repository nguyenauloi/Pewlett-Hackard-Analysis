# Pewlett-Hackard-Analysis

## **Overview of the Analysis**

The purpose of this analysis is to assist our coworker, Bobby, in determining the number of retiring employees by title and identify employees who are eligibile to participate in a mentorship program. This analysis hopes to get ahead of the 'silver tsunami' as many of the current employees reach retirement.

## Results
Through the various tables we created [retirement_titles.csv, retiring_titles.csv, unique_titles.csv, and mentorship_eligibilty.csv] we are able to identify the following:
 - 30% of the company will join the 'silver tsunami' soon
    - 72,458 of the 240,124 current employees
 - 64% of the '(soon-to-be) silver tsunami' employees hold senior roles within the company
    - 57,668 of the 90,398 current, retirement-eligible employees
 - The remaining 36% of the company hold other key positions in the company such as:
    - 14,222 Engineers
    - 12,243 Staff 
    - 4,502  Technique Leaders
    - 1,761  Assistant Engineers
    - 2      Managers
 - Although we are getting ahead of the 'silver wave', there are not enough employees who qualify for the program to replace the senior level employees near retirement. 
    - 1,549 current employees are eligible for the mentorship program
    - The criteria for joining this program was current employees who were born in 1965
 
## Summary
 - With almost one-third of the company retiring soon, and over half of that number being senior-level staff, the next few years seem like they will be turbulant for Pewlett Hackard. The mentorship program seems more important than ever with the looming threat of the 'silver wave' for the company. Though, it would be important mention that age, alone, was the only criteria for the mentorship program. If we improved this criteria to become more merit-based then, I believe, that we would see a better reflection of the future potential of the company. 
 
## Resources 
 - Data Source(s):
    - departments.csv
    - dept_emp.csv
    - dept_manager.csv
    - employees.csv
    - salaries.csv
    - titles.csv
### ERD
![alt text](https://github.com/nguyenauloi/Pewlett-Hackard-Analysis/tree/main/Resources "EmployeesDB.png")
 - Software:
    - VSCode 1.72.2 (user setup)
    - pgAdmin 4
    - PostgreSQL 11.17
    - Git Bash 2.37.1.windows.1