# Pewlett-Hackard-Analysis

## Overview
The purpose of this analysis was to determine the number of retiring employees by title and to accurately identify which employees would be eligible to participate in the mentorship program. 

## Resources
CSV Files:
- departments.csv
- dept_emp.csv
- dept_manager.csv
- employees.csv
- salaries.csv
- titles.csv

## Software:
- SQL
- PostgreSQL
- pgAdmin

## Results
It is very clear that Pewlett Hackard needs to invest in some sort of future planning since the total number of employees due to retire is 90,398. 

 - Out of the title categories, "Staff" will see the biggest loss from employees potentially retiring. That is almost 36% which is a huge deficit. Pewlett Hackard will have to find a very enticing hiring campaign to fill that talent in order to compensate for that kind of loss. 

![this is an image](https://github.com/eneubauer2022/Pewlett-Hackard-Analysis/blob/main/Resources/retiring_titles.png)

- The good news is that the second largest group with the potential of openings due to retirements - are the Senior Engineer category. This will potentially open up a possibility for the company to offer promotions to their younger generations and help build into their careers. This is why offering the mentorship program is such a great idea! 

![this is an image](https://github.com/eneubauer2022/Pewlett-Hackard-Analysis/blob/main/Resources/mentorship_eligibilty.png)

- There are only 1,940 employees eligible for the mentorship program. The only way for the program is work is for each mentor to take on several mentees - which could become overwhelming depending on how involved each mentor is. 

- It is also important to consider how this will affect the departments as well. If we run a query just focused on what titles need to be filled in what departments - we get a snapshot into what each departments needs will be over the next couple of years. For instance, the Sales department will see a serious deficit in their Senior Staff if the silver tsunami retires soon:

![this is an image](https://github.com/eneubauer2022/Pewlett-Hackard-Analysis/blob/main/Resources/positions_by_departments.png)

- By focusing on what departments will see the most turn over, we can focus on the senior staff within those departments to implement a mentorship program right away. By focusing on the titles "Senior Engineer", "Senior Staff", "Technique Leader", "Manager" - we can identify what departments have potential mentors. 

![this is an image](https://github.com/eneubauer2022/Pewlett-Hackard-Analysis/blob/main/Resources/eligible_employees_assumed.png)



